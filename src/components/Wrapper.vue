<template>
  <v-container >
    <div id="contain">
      <div class="firstParagraph hidden-sm-and-down">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus culpa quod eum, nulla error blanditiis tempora, ullam doloremque reprehenderit nostrum labore molestiae necessitatibus dolorum porro! Repellendus illo unde maxime praesentium!</p>
      </div>
      <div class="secondParagraph">
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Error deserunt exercitationem harum, consectetur quaerat eum et nihil ducimus quis corporis, blanditiis architecto modi alias deleniti necessitatibus earum voluptatibus eaque amet. Lorem ipsum dolor sit amet consectetur, adipisicing elit. Error deserunt exercitationem harum, consectetur quaerat eum et nihil ducimus quis corporis, blanditiis architecto modi alias deleniti necessitatibus earum voluptatibus eaque amet.</p>
      </div>
    </div>
    <v-parallax id="parallax" src="https://sourcingjournal.com/wp-content/uploads/2019/09/leather.jpg" height="500" class="mt-5">
      <div class="parallaxCont">
        <p class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam necessitatibus dolor sit, blanditiis officia earum delectus voluptatem distinctio quas harum. Excepturi illum accusantium quisquam velit sed magnam quis temporibus repudiandae!</p>
      </div>
    </v-parallax>
    <v-layout row wrap class="mt-10">
      <v-flex xs12 sm5 class="text-center mt-5" id="wrapper1">
        <v-icon x-large class="mt-10 mb-10">mdi-motorbike</v-icon>
        <p class="pl-5 pr-5 mb-15">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit, optio molestias dolores, nostrum est sed accusantium quod culpa harum dolorum saepe quos soluta magni cupiditate quidem suscipit quibusdam praesentium perspiciatis.</p>
      </v-flex>
      <v-flex xs12 sm5 class="text-center mt-5" id="wrapper2">
        <v-icon x-large class="mt-10 mb-10">mdi-car</v-icon>
        <p class="pl-5 pr-5 mb-15">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Non nisi vitae dignissimos quisquam itaque dolores harum voluptatibus quia, magnam ducimus optio nostrum quod fugiat corrupti omnis possimus sapiente accusantium dolore!</p>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
  export default {
    name: 'Wrapper',

    data: () => ({

    }),
  }
</script>

<style scoped>
#contain{
  height:580px;
  max-height:850px;
  background-image: url("https://thumbs.dreamstime.com/b/front-leather-seats-blue-read-stitched-car-interior-parts-inside-138098214.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  position:relative;
  margin-bottom:100px
}

.parallaxCont{
  display:flex;
  justify-content: center;
  align-content: center;
  color:black;
  background:linear-gradient(80deg, rgb(241, 78, 13), rgb(241, 192, 84), rgb(250, 220, 180));
  opacity:0.8;
  border-radius: 50px
}

.parallaxCont p{
  padding:15px
}

.firstParagraph{
  background-color:cadetblue;
  opacity: 0.8
}

.firstParagraph p{
  margin-left:5%;
  margin-right:5%;
  text-align: center;
  font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

.secondParagraph{
  background-color: cadetblue;
  opacity:0.8;
  position: absolute;
  bottom:0;
  height:auto;
}

.secondParagraph p{
  padding-top:2%;
  margin-left:5%;
  margin-right:5%;
  text-align: center;
  font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

#wrapper2{
  margin-left:auto;
  margin-right:auto;
}

#wrapper1{
  margin-left:auto;
  margin-right:auto
}

.icon{
  color:Green
}
</style>
