<template>
  <v-card class="card"
   
    color="grey"
    dark
    height="472"
    width="328"
  >
    <v-card-text>
        <div class="font-weight-bold text_card">Conversion
        </div>
      <v-sheet color="rgba(0, 0, 0, .12)">
        <v-sparkline
          :value="value"
          color="rgba(255, 255, 255, .7)"
          height="256"
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
    }
    .text_card{
        font-size: 24px;
        padding: 32px 94px 32px 32px;
    }
</style>