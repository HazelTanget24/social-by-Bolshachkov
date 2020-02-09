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
      <!-- Начало профиля-->
      <v-list-item two line>
        <v-list-item-avatar>
          <img src="https://i.pinimg.com/736x/76/ac/2e/76ac2e806dff70aaf5bb016cbb9224e8--finn-the-human-adventure-time.jpg">
        </v-list-item-avatar>
        <v-list-item-content class="text-left">
          <v-list-item-title class="font-weight-black">
            Sociallink
          </v-list-item-title>
          <v-list-item-subtitle>
            adsadsasda
          </v-list-item-subtitle>

        </v-list-item-content>   
      </v-list-item>
      <!-- Конец профиля-->

      <v-divider class="my-2"></v-divider>

      <v-list-item link :to="путь">

        <v-list-item-icon>
          <v-icon>mdi-home-outline</v-icon>
        </v-list-item-icon>

        <v-list-item-content>
          <v-list-item-title class="text-left">
            Главная
          </v-list-item-title>
        </v-list-item-content>    

      </v-list-item>

      <v-list-item link :to="путь">

        <v-list-item-icon>
          <v-icon>mdi-account</v-icon>
        </v-list-item-icon>

        <v-list-item-content>
          <v-list-item-title class="text-left">
            Мой профиль
          </v-list-item-title>
        </v-list-item-content>    

      </v-list-item>

      <v-list-item link :to="путь">

        <v-list-item-icon>
          <v-icon>mdi-account-multiple-plus</v-icon>
        </v-list-item-icon>

        <v-list-item-content>
          <v-list-item-title class="text-left">
            Найти друзей
          </v-list-item-title>
        </v-list-item-content>    

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
