<template>
    <div>
        <v-container class="main-section3" fluid pa-0>
            <v-img 
              class="main-section3bg"
              
              :src="require(`@/assets/media/demoIdSection.webp`)"
      
            >
              <v-container>
                <v-row no-gutters>
                  <v-col cols="12" sm="6" class="content mt-10">
                    <v-card-title class="white--text pt-10">
                      <div>
                        <h1>GET YOUR DEMO ID</h1>
                      </div>
                      <v-text class="mt-10">
                        <div class="main-content">
                          Lorem ipsum dolor sit amet consectetur adipisicing elit.
                          Numquam placeat nulla, quam odio error reprehenderit
                          perferendis ducimus corrupti. Dignissimos, vel.
                        </div>
                      </v-text>
                      <v-card class=" card mt-10" elevation="0" >
                        <v-hover v-slot="{ hover }">
                          <v-btn
                           class="rounded-0 pt-7 pb-7"
                            outlined
                            :style="{ 'background-color': hover ? '#07083A' : 'transparent' }"
                          >
                          +91 99988 99988
                          </v-btn>
                        </v-hover>
                        <v-hover v-slot="{ hover }">
                          <v-btn
                           class="rounded-0 pt-7 pb-7"
                            outlined
                            :style="{ 'background-color': hover ? '#07083A' : 'transparent' }"
                          >
                          +91 99988 99988
                          </v-btn>
                        </v-hover>
      
                      </v-card>
                    </v-card-title>
                  </v-col>
      
                  <v-col cols="12" sm="6" >
                    
                      <v-img
                        :src="require(`@/assets/media/Design.webp`)"
                        max-width="364"
                        class=" main-section3img ml-16"
      
                      >
                      </v-img>
                    
                  </v-col>
                </v-row>
              </v-container>
            </v-img>
          </v-container>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

  .banner-img {
  height: 100vh;
  background: transparent;
  color: aliceblue;
  }
  .card {
  background-color: transparent;
  color: white;
  }
  .num {
  max-width: 100%;
  max-height: 100%;
  }
  @media only screen and (min-width: 1024px) {
  .content {
    padding: 30px;
    z-index: 2;
  }
  .tradebg-img{
    z-index: 1;
  }
  .bg3{
    z-index: 1;
  }
  .hand-img{
    z-index:2;
  }
  .main-section3{
    position: relative;
    z-index: 1111;
  }
  .main-section3bg{
    position: initial;
  }
  .main-section3img{
    position:absolute;
    z-index: 1;
    bottom: -33px
  }
  .v-card__title{
    word-break: break-word;
    line-height: inherit;
  } 
  h1{
    font-family: 'Bebas Neue', cursive;
  }
  }
  .main-content{
    font-family: 'Montserrat', sans-serif;
    word-break: break-word;
}
@media only screen and (min-width: 300px) {
    h1{
        font-family: 'Bebas Neue', cursive;
      }
      .v-card__title{
        word-break: break-word;
        line-height: inherit;
      } 

}
</style>