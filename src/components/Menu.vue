<template>
  <div class="text-xs-center">
    <v-app-bar class="nav_menu" height="56">
       
    <div class="center">
        <a href="#" class="promotion-btn das">Dashboard</a>
    </div>   
    <div class="center">
        <a href="#" class="promotion-btn">Inbox</a>
    </div>  
    <div class="center">
        <a href="#" class="promotion-btn">Security</a>
    </div>  
    <div class="center">
        <a href="#" class="promotion-btn cal">Calendar</a>
    </div>   
    <v-icon aria-hidden="false">
        mdi-apps
    </v-icon>  
    <div class="center">
        <a href="#" class="promotion-btn data">28 October 2019</a>
    </div>  
    </v-app-bar>
  </div>
</template>
<style >
 .promotion-btn {
  /* other styles */
  display: block;
  width: 100px;
  margin-left: auto;
  margin-right: auto;
  text-decoration: none;
  color:#000000;
  font-family: Montserrat;
font-style: bold;
font-weight: normal;
font-size: 14px;
line-height: 20px;
/* identical to box height, or 143% */

display: flex;
align-items: center;
letter-spacing: 0.25px;
}

.das{
    margin-right: 40px;
    
width: 79px;
height: 20px;
left: 0px;
top: 2px;

/* Body 2 / Montserrat */

font-family: Montserrat;
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 20px;
/* identical to box height, or 143% */

display: flex;
align-items: center;
letter-spacing: 0.25px;

color: #000000;

}


.data{
     margin: 780px;
}

@import url('https://fonts.googleapis.com/css?family=Montserrat&display=swap');
.nav_menu {
    font-family: 'Montserrat', sans-serif;
    font-weight: 900;
}
.promotion-btn{
    font-family: 'Montserrat', sans-serif;
    font-weight: 900;
    font-color:#000000;
}

</style>