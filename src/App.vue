<template>
    <v-app id="app">
      <v-navigation-drawer
          color = "amber"
          white
          expand-on-hover
          hide-overlay
          permanent
          right
          app
      
        >
      <v-list
          nav 
          shaped
          dense
          color="amber"
        >
      <v-list-item link>
        asdasd
      </v-list-item>
      <v-list-item>
        asdasd
      </v-list-item>
      </v-list> 

      </v-navigation-drawer>
    
    <v-content class="px-12 py-3">
      <v-container fluid>
        <router-view/>
      </v-container>
    </v-content>

  </v-app>
</template>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}

.v-list-item--link:hover{
  background-color: #FFB300;
}
</style>
