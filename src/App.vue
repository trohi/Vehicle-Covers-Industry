<template>
  <v-app>
    <v-app-bar extended prominent dark elevation="20" src="https://thumbs.dreamstime.com/b/black-leather-texture-car-seats-background-34327593.jpg">
      <v-app-bar-nav-icon class="hidden-md-and-up" v-model="drawer" @click="drawer = !drawer"></v-app-bar-nav-icon>
      <v-toolbar-title id="naslov">Autopresvlake</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn text elevation="24" class="hidden-sm-and-down"> <v-icon>mdi-cellphone</v-icon> +387 61-xxx-xxx</v-btn>
      <template #extension class="links">
        <v-spacer></v-spacer>
          <v-btn rounded elevation="20" class="ml-2 mr-2 secondary hidden-sm-and-down" >Link1</v-btn>
          <v-btn rounded elevation="20" class="ml-2 mr-2 secondary hidden-sm-and-down" >Link2</v-btn>
          <v-btn rounded elevation="20" class="ml-2 mr-2 secondary hidden-sm-and-down" >Link3</v-btn>
          <v-btn rounded elevation="20" class="ml-2 mr-2 secondary hidden-sm-and-down" >Link4</v-btn>
          <v-btn rounded elevation="20" class="ml-2 mr-2 secondary hidden-sm-and-down" >Link5</v-btn>
          <v-spacer></v-spacer>
      </template>
    </v-app-bar>
    <v-navigation-drawer
       dark
       temporary 
       absolute
       v-model="drawer"
       >
      <v-list-item class="mt-10">
        <v-list-item-content>
          <v-list-item-title class="title">
            Autopresvlake
          </v-list-item-title>
        </v-list-item-content>
      </v-list-item>
      <v-divider></v-divider>

      <v-list
        nav
        class="mt-10"
      >
        <v-list-item>
          <v-list-item-icon>
            <v-icon>mdi-home</v-icon>
          </v-list-item-icon>
          <v-list-item-content>
            <v-list-item-title>Home</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
         <v-list-item>
          <v-list-item-icon>
            <v-icon>mdi-yin-yang</v-icon>
          </v-list-item-icon>
          <v-list-item-content>
            <v-list-item-title>Some other link</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
         <v-list-item class="mb-10">
          <v-list-item-icon>
            <v-icon>mdi-xmpp</v-icon>
          </v-list-item-icon>
          <v-list-item-content>
            <v-list-item-title>Another link</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
        <v-divider></v-divider>
        <v-list-item>
          <v-list-content>
            <v-list-item-title elevation="24" class="mt-5 text-center"> <v-icon>mdi-cellphone</v-icon> +387 61-xxx-xxx</v-list-item-title>
          </v-list-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
    <v-main>
      <Wrapper/>
      <Carousel/>
      <Footer/>
    </v-main>
  </v-app>
</template>

<script>
import Wrapper from './components/Wrapper';
import Carousel from './components/Carousel';
import Footer from './components/Footer';

export default {
  name: 'App',

  components: {
    Wrapper,
    Carousel,
    Footer
  },

  data: () => {
    return {
        drawer:false
      }
  },
};
</script>

<style scoped>
#naslov{
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  font-weight:bold;
  font-size:45px;
  margin-left:auto;
  color:white;
  text-shadow: 0 2px 4px rgba(1, 199, 199, 0.4);
  width: auto
}

#drawer{
  z-index:12
}
</style>
