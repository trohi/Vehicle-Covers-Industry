<template>
    <v-footer dark padless>
        <v-card 
        class="teal lighten-1 white--text text-center"
        >
          <v-card-text>
              <v-icon class="ml-5 mr-5">mdi-chart-donut</v-icon>
              <v-icon class="ml-5 mr-5">mdi-chart-pie</v-icon>
              <v-icon class="ml-5 mr-5">mdi-chart-bubble</v-icon>
              <v-icon class="ml-5 mr-5">mdi-shopping</v-icon>
              </v-card-text>
          <v-card-text 
          class="mr-4 white--text">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quos soluta illum possimus exercitationem voluptatem sequi omnis minima magnam temporibus eligendi, dolore inventore eum accusantium a ducimus minus quas reprehenderit quisquam?
          </v-card-text>
          <v-divider></v-divider>
          <v-card-text> Vue.Js <strong>@2020</strong> </v-card-text> <v-btn class="arrowIcon" depressed fab @click="$vuetify.goTo('#naslov', 100)"> <v-icon large>mdi-chevron-double-up</v-icon></v-btn>
        </v-card>
    </v-footer>
</template>

<script>
export default {
    name:'Footer',
    data(){
        return {

        }
    }
}
</script>

<style>
.arrowIcon{
    margin-right:15px;
    margin-top:-7%;
    float:right
}
</style>
