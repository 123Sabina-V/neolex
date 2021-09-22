<template>
  <v-app>
    <Header />
    <Menu />
    <div class="row">
      <Conversion />
      <Users />
      <Revenue />
    </div>
    <div class="row">
      <Calendar />
        <a class="orders">Orders</a>     
          <v-btn 
            aria-hidden="false"
            width="40"
            height="40"
            class="btn-stg">
            <v-icon>mdi-cog</v-icon>
            </v-btn>  
            <v-btn
            height="40"
            width="156"
            class="btn-dwnl">Download CSV
            <v-icon>mdi-arrow-collapse-down</v-icon></v-btn>  
            <v-btn
            height="40"
            width="112"
            class="btn-exp">Export
            <v-icon>mdi-arrow-collapse-up</v-icon></v-btn>
            <div class="row"><Table /></div>    
          
    </div>
    <v-main> </v-main>
  </v-app>
</template>

<script>
import Conversion from "./components/Conversion.vue";
import Users from "./components/Users.vue";
import Header from "./components/Header.vue";
import Menu from "./components/Menu.vue";
import Revenue from "./components/Revenue.vue";
import Calendar from "./components/Calendar.vue";
import Table from "./components/Table.vue";

export default {
  name: "App",

  components: {
    Header,
    Menu,
    Conversion,
    Users,
    Revenue,
    Calendar,
    Table
  },

  data: () => ({
    //
  }),
};
</script>

<style scoped>
.orders {
 
  font-family: Montserrat;
  font-weight: bold;
  font-size: 24px;
  margin: 48px 400px 24px 16px;
  color: #333333;
 
}
.row {
  flex: none;
}
.btn-dwnl{
  margin: 48px 16px 24px 16px;
   font-family: 'Montserrat', sans-serif;
    font-weight: 900;
    font-size: 11px;
}
.btn-exp{
  margin: 48px 16px 24px 16px;
  font-family: 'Montserrat', sans-serif;
    font-weight: 900;
    font-size: 11px;
}
.btn-stg{
   margin: 48px 16px 24px 16px;
}
@import url('https://fonts.googleapis.com/css?family=Montserrat&display=swap');
.row {
    font-family: 'Montserrat', sans-serif;
    font-weight: 900;
}
</style>
