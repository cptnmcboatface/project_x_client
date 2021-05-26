<template>
  <v-container>
    <!-- Hello -->
    <v-row>
      <v-col cols="12" sm="6" height="400" align-self="center">
        <container class="mb-4">
          <h1
            class="text-h1 text-md-h2 text-sm-h2 text-xs-h3 font-weight-light"
          >
            {{ $t('landing.TITLE') }}
          </h1>
          <p class="text-overline text-sm-p text-xs-p font-weight-light">
            Welcome kickstart your store by becoming Pakistan's 1st Multi-Vendor
            Platform for Fashion.
          </p>
        </container>
        <v-flex align-self-center="true" grow="true">
          <v-btn outlined> Get Started </v-btn>
        </v-flex>
      </v-col>
      <v-col class="" cols="12" sm="6" order-sm="1">
        <v-img
          lazy-src="https://i.ibb.co/qyYktpj/Work-from-home.jpg"
          max-height="400"
          src="https://i.ibb.co/qyYktpj/Work-from-home.jpg"
        ></v-img>
      </v-col>
    </v-row>
    <!-- Who are We -->
    <v-row>
      <v-col cols="12">
        <h1 class="text-h4 font-weight-light">Who are we?</h1>
      </v-col>
      <v-col cols="12" sm="6">
        <v-img
          lazy-src="https://i.ibb.co/RD0N9W5/Corporate-portrait-of-office-workers-and-employees-flat-vector-illustration-Cartoon-happy-business-t.jpg"
          max-height="400"
          src="https://i.ibb.co/RD0N9W5/Corporate-portrait-of-office-workers-and-employees-flat-vector-illustration-Cartoon-happy-business-t.jpg"
        ></v-img>
      </v-col>
      <v-col cols="12" sm="6" height="400" align-self="center">
        <p class="text-h5 text-sm-p text-xs-p font-weight-light">
          We are you &#60;3
        </p>
        <p class="text-overline text-sm-p text-xs-p font-weight-light">
          We are a dynamic team of people trying to bring about a revolution in
          Pakistan's fashion industry with your help.
        </p>
        <v-btn outlined> Join the revolution </v-btn>
      </v-col>
    </v-row>
    <v-row>
      <v-col cols="12">
        <h1 class="text-h4 font-weight-light">What are we building?</h1>
      </v-col>
      <v-col cols="12">
        <p class="text-p font-weight-light">
          We believe Pakistan is going through a digital revolution. With new
          fashion stores opening up everyday, it's hard to keep track of what
          store offers what.
        </p>
        <p class="text-p font-weight-light">
          What we hope to do is to bring all these stores together on one
          platform. Where both big and small scale stores and their products are
          available to people.
        </p>
      </v-col>
    </v-row>
  </v-container>
</template>
