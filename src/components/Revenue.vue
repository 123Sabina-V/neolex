<template>
  <v-card 
    class="mx-auto card"
    color="grey"
    dark
    height="472"
    width="612"
     
  >
    <v-card-text>
      <v-sheet color="rgba(0, 0, 0, .12)">
        <v-sparkline
          :value="value"
          color="rgba(255, 255, 255, .7)"
          height="100"
          padding="24"
          stroke-linecap="round"
          smooth
        >
          <template v-slot:label="item">
            ${{ item.value }}
          </template>
        </v-sparkline>
      </v-sheet>
    </v-card-text>

    <v-card-text>
      <div class="card">
        Sales Last 24h
      </div>
    </v-card-text>

    <v-divider></v-divider>

    <v-card-actions class="card">
      <v-btn
        block
        text
      >
        Go to Report
      </v-btn>
    </v-card-actions>
  </v-card>
</template>

<script>
  export default {
    data: () => ({
      value: [
        423,
        446,
        675,
        510,
        590,
        610,
        760,
      ],
    }),
  }
</script>
<style scoped>
    .card{
        margin: 24px 16px 24px 16px;
        font-family: 'Montserrat', sans-serif;
    font-weight: 900;
    }
    .text_card{
        font-size: 24px;
        padding: 32px 94px 32px 32px;
    }
    @import url('https://fonts.googleapis.com/css?family=Montserrat&display=swap');

</style>