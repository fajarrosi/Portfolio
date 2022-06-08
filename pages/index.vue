<template>
<v-app>
  <v-main class="bg-grey">
    <v-container fluid>
      <v-row align="center" style="height:100vh;">
        <v-col cols="12" md="6">
          <v-row justify="center" justify-md="end">
            <v-col md="6" cols="11" class="text-center text-md-left">
              <h1 class="primary--text">Fajar Ilham Rosi</h1>
              <h3>I'm <span class="secondary--text"> Frontend Developer </span></h3>
              <v-row>
                <v-col>
                  <v-btn
                    depressed
                    color="primary"
                    fab
                    dense
                    small
                    @click="openGithub"
                  >
                    <v-icon dark>
                      mdi-github
                    </v-icon>
                  </v-btn>
                </v-col>
                
              </v-row>
            </v-col>
          </v-row>
        </v-col>
        <v-col cols="12" md="6" class="text-center text-md-left">
          <img src="~assets/beranda.png" alt="ilustrasi beranda" srcset="~assets/beranda.png" width="100%" height="100%" style="max-width:400px;">
        </v-col>
        <v-col cols="12" class="text-center">
          <v-btn
            depressed
            color="primary"
            fab
            dense
            small
            @click="scrollTo"
          >
            <v-icon dark>
              mdi-chevron-double-down
            </v-icon>
          </v-btn>
        </v-col>
      </v-row>
    </v-container>
    <v-container>
      <v-row id="project" style="min-height:600px;">
        <v-col class="text-center">
          <h1 class="primary--text">Projects I've Done</h1>
        </v-col>
      </v-row>
    </v-container>
  </v-main>
</v-app>
</template>

<script>
export default {
  name: 'IndexPage',
  methods: {
    openGithub() {
      window.open("https://github.com/fajarrosi",'_blank');
    },
    scrollTo() {
      window.open("#project",'_self');
    }
  }
}
</script>
