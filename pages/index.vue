<template>
<v-app>
  <v-app-bar
    app
    color="transparent"
    style="box-shadow:none; padding:20px"
  >
    <v-toolbar-title class="font-weight-light headline white--text">
      <h1 style="font-size:16px; font-weight:500;">
      SAMUEL TENGEY
      </h1>
    </v-toolbar-title>
    <v-spacer></v-spacer>
      <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>
      <v-btn icon>
        <v-icon>mdi-heart</v-icon>
      </v-btn>
      <v-btn icon>
        <v-icon>mdi-dots-vertical</v-icon>
      </v-btn>
  </v-app-bar>
    <v-main class="ma-0 pa-0">
      <section id="hero" class="hidden-sm-and-down">
        <v-row no-gutters>
            <v-col>
            <v-theme-provider dark>
              <v-container fill-height style="background-color:#000000c9">
                <v-row
                  class="white--text"
                >
                  <v-col
                    class="white--text"
                    cols="9 mx-auto"
                  >
                  <div class="anim">
                    <span
                      class="font-weight-light display-1 underline-small mt-5" 
                    >
                      WELCOME TO MY SITE
                    </span>
                    <p style="font-size:15px" class="mt-6">
                      I take pleasure in helping people to discover themselves, their purpose and assignment, 
                      as well as the hidden leader trapped in them. I distribute transformational ideas that have and
                       continue to revolutionise several people. 
                       <br/><br/>
                       My passion is to see people identify their gifts and purpose, get the right education to deliver their purposes, 
                       and to discover the leader trapped in them. 
                       <br/><br/>
                       Discovering purpose and discovering the leadership potential 
                    </p>
                  </div>
                  <v-btn
                    class="align-self-end mx-auto"
                    fab
                    outlined
                    @click="$vuetify.goTo('#about-me')"
                  >
                    <v-icon>mdi-chevron-double-down</v-icon>
                  </v-btn>
                  </v-col>
                </v-row>
              </v-container>
            </v-theme-provider>
            </v-col>
            
          <v-col cols="6">
          <v-img
            height="100vh"
            width="100%"
            gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
            src="https://scontent.facc6-1.fna.fbcdn.net/v/t1.0-9/143660503_10215407519621156_1246599223785698553_n.jpg?_nc_cat=101&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeFaZT543UK0Y2Trtn0qHI17hwFRm6ff1_yHAVGbp9_X_DB02wI59Sk5fHsV8gE6CV18otFFqOBr2OH1d1Uk6odV&_nc_ohc=ORPmNEMyyYkAX_GM5HV&_nc_ht=scontent.facc6-1.fna&oh=1b6cd286980eba2f8d1af45eaeea1042&oe=606C56C0"
            style="contain"
          >
          </v-img>
          </v-col>
        </v-row>
      </section>
      <section id="hero" class="hidden-md-and-up"> 
        <v-row no-gutters>
            <v-col>
            <v-theme-provider dark>
              <v-img
                height="100vh"
                width="100%"
                src="https://scontent.facc6-1.fna.fbcdn.net/v/t1.0-9/143660503_10215407519621156_1246599223785698553_n.jpg?_nc_cat=101&ccb=1-3&_nc_sid=730e14&_nc_eui2=AeFaZT543UK0Y2Trtn0qHI17hwFRm6ff1_yHAVGbp9_X_DB02wI59Sk5fHsV8gE6CV18otFFqOBr2OH1d1Uk6odV&_nc_ohc=ORPmNEMyyYkAX_GM5HV&_nc_ht=scontent.facc6-1.fna&oh=1b6cd286980eba2f8d1af45eaeea1042&oe=606C56C0"
                style="contain"
                gradient="to top, rgba(0,0,0,.6), rgba(0,0,0,.5)"
              >
              <div style="padding:15px; margin-top:40vh">
                    <span
                      class="font-weight-light display-1 underline-small mt-5" 
                    >
                      WELCOME TO MY SITE
                    </span>
                    <p style="font-size:15px" class="mt-6">
                      I take pleasure in helping people to discover themselves, their purpose and assignment, 
                      as well as the hidden leader trapped in them. I distribute transformational ideas that have and
                       continue to revolutionise several people. 
                       <br/><br/>
                       My passion is to see people identify their gifts and purpose, get the right education to deliver their purposes, 
                       and to discover the leader trapped in them. 
                       <br/><br/>
                       Discovering purpose and discovering the leadership potential 
                    </p>
                  </div>
              </v-img>
            </v-theme-provider>
            </v-col>
        </v-row>
      </section>

      <section id="about-me">
        <div class="py-6"></div>

        <v-container class="text-center">
          <h2 class="display-1 font-weight-light mb-3" style="18px">LIFE CONVICTION AND PERSONAL VALUE STATEMENT</h2>

          <v-responsive
            class="mx-auto mb-8"
            width="56"
          >
            <v-divider class="mb-1"></v-divider>
          </v-responsive>

          <v-responsive
            class="mx-auto font-weight-light mb-8"
          >
          Whilst I am fully aware that there are several people who have similar gifts, anointing, potential, and educational qualifications and as me, I am persuaded nonetheless, beyond every doubt that, I am uniquely different, that I possess a unique potential, that I have a unique gift, and that I have a unique distinct and well-carved out assignment to deliver to my generation. I believe that whereas any other 
          person can do most of the things I do to some degree, there is no single human being on this planet who has been endowed with the same level and character of potential, gifts, talents, passion and anointing like me. 
          </v-responsive>

          <div></div>
        </v-container>

        <div class="py-6"></div>
      </section>

      <section
        id="features"
        class="grey lighten-3"
      >
        <div class="py-6"></div>

        <v-container class="text-center">
          <h2 class="display-1 font-weight-light mb-3" style="18px">BOOKS</h2>

          <v-responsive
            class="mx-auto mb-12"
            width="56"
          >
            <v-divider class="mb-1"></v-divider>

            <v-divider></v-divider>
          </v-responsive>

          <v-row>
            <v-col
              v-for="({ year, title, image }, i) in books"
              :key="i"
              cols="12"
              md="4"
            >
            <v-card>
            <v-img
              :src="image"
              class="white--text align-end"
              gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
              height="400px"
            >
              <v-card-title 
                style="width:90%;text-align:left;"
              >{{title}} <br/>{{year}}</v-card-title>
            </v-img>
          </v-card>
            </v-col>
          </v-row>
          <v-btn text class="mt-3">view more</v-btn>
        </v-container>

        <div class="py-6"></div>
      </section>


<section
        id="features"
        class="grey lighten-3"
      >

        <v-container class="text-center">
          <h2 class="display-1 font-weight-light mb-3" style="18px">AUDIOS</h2>

          <v-responsive
            class="mx-auto mb-6"
            width="56"
          >
            <v-divider class="mb-1"></v-divider>

            <v-divider></v-divider>
          </v-responsive>

          <v-row>
            <v-col
              v-for="({  title, image,color,artist }, i) in audio"
              :key="i"
              cols="12"
              md="4"
            >
            <v-card
            :color="color"
            dark
          >
            <div class="d-flex flex-no-wrap justify-space-between">
              <div>
                <v-card-title
                  style="text-align:left;font-size:14px"
                  v-text="title"
                ></v-card-title>

                <v-card-subtitle v-text="artist"
                  style="text-align:left;"></v-card-subtitle>

                <v-card-actions>

                  <v-btn
                    class="ml-2 mt-5"
                    outlined
                    rounded
                    small
                  >
                    START RADIO
                  </v-btn>
                </v-card-actions>
              </div>

              <v-avatar
                class="ma-3"
                size="125"
                tile
              >
                <v-img :src="image"></v-img>
              </v-avatar>
            </div>
          </v-card>
            </v-col>
          </v-row>
          <v-btn text class="mt-3">view more</v-btn>
        </v-container>

        <div class="py-12"></div>
      </section>

          


      <section id="stats">
        <v-parallax
          :height="$vuetify.breakpoint.smAndDown ? 700 : 500"
          src="https://images.unsplash.com/photo-1510915228340-29c85a43dcfe?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80"
        >
          <v-container fill-height>
            <v-row class="mx-auto">
              <v-col
                v-for="[value, title] of stats"
                :key="title"
                cols="12"
                md="3"
              >
                <div class="text-center">
                  <div
                    class="display-3 font-weight-black mb-4"
                    v-text="value"
                  ></div>

                  <div
                    class="title font-weight-regular text-uppercase"
                    v-text="title"
                  ></div>
                </div>
              </v-col>
            </v-row>
          </v-container>
        </v-parallax>
      </section>

      <section id="blog">
        <div class="py-12"></div>

        <v-container>
          <h2 class="display-2 font-weight-bold mb-3 text-uppercase text-center">Blog</h2>

          <v-responsive
            class="mx-auto mb-12"
            width="56"
          >
            <v-divider class="mb-1"></v-divider>

            <v-divider></v-divider>
          </v-responsive>

          <v-row>
            <v-col
              v-for="({ src, text, title }, i) in articles"
              :key="i"
              cols="12"
              md="4"
            >
              <v-img
                :src="src"
                class="mb-4"
                height="275"
                max-width="100%"
              ></v-img>

              <h3
                class="font-weight-black mb-4 text-uppercase"
                v-text="title"
              ></h3>

              <div
                class="title font-weight-light mb-5"
                v-text="text"
              ></div>

              <v-btn
                class="ml-n4 font-weight-black"
                text
              >
                Continue Reading
              </v-btn>
            </v-col>
          </v-row>
        </v-container>

        <div class="py-12"></div>
      </section>

      <!-- <v-sheet
        id="contact"
        color="#333333"
        dark
        tag="section"
        tile
      >
        <div class="py-12"></div>

        <v-container>
          <h2 class="display-2 font-weight-bold mb-3 text-uppercase text-center">Contact Us</h2>

          <v-responsive
            class="mx-auto mb-12"
            width="56"
          >
            <v-divider class="mb-1"></v-divider>

            <v-divider></v-divider>
          </v-responsive>

          <v-theme-provider light>
            <v-row>
              <v-col cols="6" class="mx-auto">
              <v-col cols="12">
                <v-text-field
                  flat
                  label="Name*"
                  solo
                ></v-text-field>
              </v-col>

              <v-col cols="12">
                <v-text-field
                  flat
                  label="Email*"
                  solo
                ></v-text-field>
              </v-col>

              <v-col cols="12">
                <v-text-field
                  flat
                  label="Subject*"
                  solo
                ></v-text-field>
              </v-col>

              <v-col cols="12">
                <v-textarea
                  flat
                  label="Message*"
                  solo
                ></v-textarea>
              </v-col>

              <v-col
                cols="12"
              >
                <v-btn
                  color="accent"
                  x-large
                >
                  Submit
                </v-btn>
              </v-col>
            </v-col>
            </v-row>
          </v-theme-provider>
        </v-container>

        <div class="py-12"></div>
      </v-sheet> -->
    </v-main>

    <v-footer
      class="justify-center"
      color="#292929"
      height="100"
    >
      <div class="title font-weight-light grey--text text--lighten-1 text-center">
        &copy; {{ (new Date()).getFullYear() }} — our app
      </div>
    </v-footer>
  </v-app>
</template>
<script>
import leadership from '~/static/leadership.jpeg';
import critical from '~/static/critical.jpeg';
import gyno from '~/static/gyno.jpeg';
import cover from '~/static/cover.jpeg';
export default {
    data () {
      return {
        cover:cover,
        articles: [
          {
            src: 'https://images.unsplash.com/photo-1423784346385-c1d4dac9893a?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80',
            title: 'Mobile first & Responsive',
            text: 'Phasellus lorem enim, luctus ut velit eget, convallis egestas eros. Sed ornare ligula eget tortor tempor, quis porta tellus dictum.',
          },
          {
            src: 'https://images.unsplash.com/photo-1475938476802-32a7e851dad1?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80',
            title: 'Think outside the box',
            text: 'Nam ut leo ipsum. Maecenas pretium aliquam feugiat. Aenean vel tempor est, vitae tincidunt risus. Sed sodales vestibulum nibh.',
          },
          {
            src: 'https://images.unsplash.com/photo-1416339442236-8ceb164046f8?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1892&q=80',
            title: 'Small changes, big difference',
            text: 'Vestibulum in dictum velit, in rhoncus nibh. Maecenas neque libero, interdum a dignissim in, aliquet vitae lectus. Phasellus lorem enim, luctus ut velit eget.',
          },
        ],
        books: [
          {
            year:"2018",
            title: 'Leadership Stripped Bare',
            image: leadership
          },
          {
            year: '2017',
            title: 'Critical Issues in Contemporary Church ',
            image: critical
          },
          {
            year: '2019',
            title: 'Gynaecology of Church Growth ',
            image: gyno
          },
        ],
        audio: [
        {
          color: '#1F7087',
          image: 'https://cdn.vuetifyjs.com/images/cards/foster.jpg',
          title: 'Critical Issues in Contemporary Church',
          artist: 'Samuel Tengey',
        },
        {
          color: '#952175',
          image: 'https://cdn.vuetifyjs.com/images/cards/halcyon.png',
          title: 'Leadership, Stewardship & Loyalty in Church',
          artist: 'Samuel Tengey',
        },
        {
          color: '#1F7087',
          image: 'https://cdn.vuetifyjs.com/images/cards/foster.jpg',
          title: 'Strategy for Turning First-Time Visitors to Committed Church Members',
          artist: 'Samuel Tengey',
        },
      ],
        stats: [
          ['24k', 'Github Stars'],
          ['330+', 'Releases'],
          ['1m', 'Downloads/mo'],
          ['5m', 'Total Downloads'],
        ],
      }
    }
}
</script>
<style scoped>
.underline-small{
  display:inline-block;
  position:relative;
  
}

.underline-small::after{
  content:'';
  height:4px;
  width:20%;
  background:white;
  position:absolute;
  left:0;
  bottom:-5px;
}

.anim {
  animation: slideInUp 1000ms ease-in-out;
}

</style>