<template>
    <div>
        <v-container fluid pa-0>
            <v-img :src="require(`@/assets/media/whatsappSection.webp`)">
              <v-container>
                <v-row no-gutters>
                  <v-col
                    cols="12"
                    sm="6"
                    class="d-flex"
                    style="align-items: center"
                  >
                    <v-img
                      :src="require(`@/assets/media/Vector-Smart-ObjectCSC.webp`)"
                      max-width="381"
                      class=""
                    >
                    </v-img>
                  </v-col>
                  <v-col cols="12" sm="6" class="content mt-10">
                    <v-card-title class="white--text pt-10">
                      <v-text>
                        <h1>GET AN ID INSTANTLY ON WHATSAPP</h1>
                      </v-text>
                      <v-text class="mt-5">
                        <h3>Get in touch with our customer care</h3>
                      </v-text>
                      <v-text class="mt-5">
                        <h4>For Any Queries, Emergencies,
                          Feedbacks or Complaints.
                          We Are Here To Help You
                          24/7 With Our Online Services.</h4>
                      </v-text>
                      <v-text class="mt-5">
                        <h4>Whatsapp us on</h4>
                        <v-hover v-slot="{ hover }">
                          <v-btn
                           class="rounded-0 pt-7 pb-7"
                            outlined
                            :style="{ 'background-color': hover ? 'green' : 'transparent' }"
                          >
                          +91 99988 99988
                          </v-btn>
                        </v-hover>
                      </v-text>
                      <v-text class="mt-5">
                        <h4>With our step-by-step guide for beginners</h4>
                        <v-hover v-slot="{ hover }">
                          <v-btn
                           class="rounded-0 pt-7 pb-7"
                            outlined
                            :style="{ 'background-color': hover ? 'green' : 'transparent' }"
                          >
                          +91 99988 99988
                          </v-btn>
                        </v-hover>
                      </v-text>
                      <v-text class="">
      
                      </v-text>
                      <v-text class="mt-10">
                        <!-- <div>
                          Lorem ipsum dolor sit amet consectetur adipisicing elit.
                          Numquam placeat nulla, quam odio error reprehenderit
                          perferendis ducimus corrupti. Dignissimos, vel.
                        </div> -->
                      </v-text>
                    </v-card-title>
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
.main-section1{
  position: relative;
  z-index: 1111;
}
.main-section1bg{
  position: initial;
}
.main-section1img{
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