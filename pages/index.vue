<template>
<v-app>
  <v-main class="bg-grey">
    <v-container  fluid>
      <v-row align="center" style="height:100vh;">
        <v-col cols="12" sm="8" md="6">
          <v-row justify="center" justify-md="end">
            <v-col md="6" cols="11">
              <h1 class="primary--text">Fajar Ilham Rosi</h1>
              <h3>I'm <span class="secondary--text"> Frontend Developer </span></h3>
              <v-row class="mt-2">
                <v-col>
                  <v-btn
                    fab
                    dark
                    small
                    color="pink"
                  >
                    <v-img src="~assets/twitter.svg" />
                  </v-btn>
                  <v-btn
                    class="mx-2"
                    fab
                    dark
                    small
                    color="pink"
                  >
                    <v-icon dark>
                      mdi-heart
                    </v-icon>
                  </v-btn>
                </v-col>
                
              </v-row>
            </v-col>
          </v-row>
        </v-col>
        <v-col cols="12" md="6">
          <v-row align="center" justify="center" justify-md="start">
            <v-col cols="7">
              <img src="~assets/beranda.png" alt="ilustrasi beranda" srcset="~assets/beranda.png" width="100%" height="100%">
            </v-col>
          </v-row>
        </v-col>
      </v-row>
    </v-container>
  </v-main>
</v-app>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
