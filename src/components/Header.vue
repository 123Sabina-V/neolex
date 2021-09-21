<template>
  <div>
    <v-app-bar class="nav_menu" color="white" height="88">
      
        <img src="img/logo.png" class="nav_img"
        width="135">
      
     
        <v-list class="v-list" width="256" >
          <v-list-item class="list-item">
            <v-avatar class="v-avatar" color="grey">
              <span class="white--text text-h5">RC</span>
            </v-avatar>
            <v-list-item link>
              <v-list-item-content>
                <v-list-item-title class="text-h8">
                  Regina Cooper
                </v-list-item-title>
                <v-list-item-subtitle>Washington, DC, USA</v-list-item-subtitle>
              </v-list-item-content>
              <v-list-item-action>
                <v-icon>mdi-menu-down</v-icon>
              </v-list-item-action>
            </v-list-item>
          </v-list-item>
        </v-list>
      
      <v-text-field
        
        class="text_field"
        filled
        label="Search text"
        append-icon="mdi-magnify"
      ></v-text-field>
      <v-icon aria-hidden="false"> mdi-settings </v-icon>
      <v-icon aria-hidden="false"> mdi-bell </v-icon>
    </v-app-bar>
  </div>
</template>

<style>
.nav_img {
  margin-right: 33px;
  
}
.nav_menu {
  height: 88px;
}
.list-item{
  margin: 0;
}
.v-avatar {
  width: 28px;
  height: 24px;
}

.text_field {
  width: 296px;
  height: 56px;
  background: #ffffff;
  border: 1px solid #dddddd;
  box-sizing: border-box;
  border-radius: 4px;
}
</style>