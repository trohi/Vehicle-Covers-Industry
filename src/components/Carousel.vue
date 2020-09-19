<template>
    <div class="carouselWrapper">
        <v-carousel>
            <v-carousel-item
            transition="fade-transition"
            src='https://thumbs.dreamstime.com/b/detail-leather-car-chair-photo-interior-52180178.jpg'
            >
            </v-carousel-item>
            <v-carousel-item
            transition="fade-transition"
            src='https://thumbs.dreamstime.com/b/car-seat-light-skin-close-up-view-small-depth-field-stock-photo-76548374.jpg'
            >
            </v-carousel-item>
            <v-carousel-item
            transition="fade-transition"
            src='https://thumbs.dreamstime.com/z/car-interior-leather-texture-horizontal-photo-48957268.jpg'
            >
            </v-carousel-item>
            <v-carousel-item
            transition="fade-transition"
            src='https://thumbs.dreamstime.com/z/front-leather-seats-blue-read-stitched-car-interior-parts-inside-138098214.jpg'
            >
            </v-carousel-item>
            <v-carousel-item
            transition="fade-transition"
            src='https://thumbs.dreamstime.com/z/part-leather-car-seat-macro-part-leather-car-seat-background-macro-photo-car-perforated-leather-background-interior-detail-170558257.jpg'
            >
            </v-carousel-item>
            <v-carousel-item
            transition="fade-transition"
            src='https://thumbs.dreamstime.com/b/closeup-shot-black-leather-car-seat-closeup-shot-black-leather-car-seat-182737922.jpg'
            >
            </v-carousel-item>
        </v-carousel>
        <div class="panelsWrapper">
        <v-expansion-panels
            popout 
            dark
            focusable
            class="my-15 teal--text">
            <v-expansion-panel>
                <v-expansion-panel-header>Automobile</v-expansion-panel-header>
                <v-expansion-panel-content>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure obcaecati, officiis ullam itaque assumenda dolorum doloribus, quos libero repudiandae, harum molestiae saepe eius enim. Molestiae nobis necessitatibus rem dolorum nesciunt!</v-expansion-panel-content>
            </v-expansion-panel>
            <v-expansion-panel>
                <v-expansion-panel-header>Motorcycle</v-expansion-panel-header>
                <v-expansion-panel-content>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure obcaecati, officiis ullam itaque assumenda dolorum doloribus, quos libero repudiandae, harum molestiae saepe eius enim. Molestiae nobis necessitatibus rem dolorum nesciunt!</v-expansion-panel-content>
            </v-expansion-panel>
            <v-expansion-panel>
                <v-expansion-panel-header>Other</v-expansion-panel-header>
                <v-expansion-panel-content>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure obcaecati, officiis ullam itaque assumenda dolorum doloribus, quos libero repudiandae, harum molestiae saepe eius enim. Molestiae nobis necessitatibus rem dolorum nesciunt!</v-expansion-panel-content>
            </v-expansion-panel>
        </v-expansion-panels>
        </div>
        <div class="breakingLine">

        </div>
        <v-container>
            <v-layout>
                <v-flex xs-10 class="d-inline-flex" id="cardContainer">
                    <v-card
                    class="mx-9 teal"
                    max-width="300"
                    >
                        <v-img
                        src="https://www.motorblog.rs/wp-content/uploads/2012/10/koza.jpg"
                        width="290"
                        height="260"
                        class=""
                        >
                        <v-card-title class="dark--text" >Example #1</v-card-title>
                        </v-img>
                        <v-card-action>
                            <v-btn dark class="my-2 ml-1"> <v-icon class="mr-2">mdi-cart</v-icon> Shop</v-btn>
                        </v-card-action>
                    </v-card>
                    <v-card
                    class="mx-9 teal"
                    max-width="300"
                    >
                        <v-img
                        src="https://www.navidiku.rs/firme/subcatimg/s1878/velike/auto-presvlake20331.jpg"
                        width="290"
                        height="260"
                        class=""
                        >
                        <v-card-title class="dark--text">Example #2</v-card-title>
                        </v-img>
                        <v-card-action>
                            <v-btn dark class="my-2 ml-1"> <v-icon class="mr-2">mdi-cart</v-icon> Shop</v-btn>
                        </v-card-action>
                    </v-card>
                     <v-card
                    class="mx-9 teal"
                    max-width="300"
                    >
                        <v-img
                        src="https://www.magazinauto.com/wp-content/uploads/2015/05/P1011272.jpg"
                        width="290"
                        height="260"
                        class=""
                        >
                        <v-card-title class="dark--text">Example #3</v-card-title>
                        </v-img>
                        <v-card-action>
                            <v-btn dark class="my-2 ml-1"> <v-icon class="mr-2">mdi-cart</v-icon> Shop</v-btn>
                        </v-card-action>
                    </v-card>
                     <v-card
                    class="mx-9 teal"
                    max-width="300"
                    >
                        <v-img
                        src="https://www.magazinauto.com/wp-content/uploads/2015/05/P1011272.jpg"
                        width="290"
                        height="260"
                        class=""
                        >
                        <v-card-title class="dark--text">Example #4</v-card-title>
                        </v-img>
                        <v-card-action>
                            <v-btn dark class="my-2 ml-1"> <v-icon class="mr-2">mdi-cart</v-icon> Shop</v-btn>
                        </v-card-action>
                    </v-card>
                    <v-card
                    class="mx-9 teal"
                    max-width="300"
                    >
                        <v-img
                        src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQ9eNTrJXf07VByt3ILd4_ze-eUFkAzW3rSzQ&usqp=CAU"
                        height="260"
                        width="290"
                        class=""
                        >
                        <v-card-title class="dark--text">Example #5</v-card-title>
                        </v-img>
                        <v-card-action>
                            <v-btn dark class="my-2 ml-1"> <v-icon class="mr-2">mdi-cart</v-icon> Shop</v-btn>
                        </v-card-action>
                    </v-card>
                    <v-card
                    class="mx-9 teal"
                    max-width="300"
                    >
                        <v-img
                        src="data:image/jpeg;base64,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"
                        height="260"
                        width="290"
                        class=""
                        >
                        <v-card-title class="dark--text">Example #6</v-card-title>
                        </v-img>
                        <v-card-action>
                            <v-btn dark class="my-2 ml-1"> <v-icon class="mr-2">mdi-cart</v-icon> Shop</v-btn>
                        </v-card-action>
                    </v-card>
                </v-flex>
            </v-layout>
        </v-container>
        <div class="breakingLine">

        </div>
    </div>
</template>

<script>
export default {
    name:'Carousel',
    data:()=>{
        return{
            
        }
    }
}
</script>

<style scoped>
.carouselWrapper{
    width:100%;
    margin:50px 0px 0px 0px;
    padding:0px
}

.breakingLine{
    height:6px;
    content:'';
    margin-bottom:3%;
    width:100%;
    background:linear-gradient(50deg, rgb(36, 58, 57), rgb(12, 36, 33), rgb(0, 9, 10))
}

.panelsWrapper{
    width:45%;
    margin-left:auto;
    margin-right:auto
}

#cardContainer{
    overflow-y:scroll;
    margin-bottom:5%
}

.v-card__title{
    background-color:teal;
    opacity:0.7
}

@media only screen and (max-width:900px){
    .panelsWrapper{
        width:100%
    }
}
</style>
