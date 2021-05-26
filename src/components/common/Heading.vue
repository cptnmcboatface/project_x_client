<template>
  <v-flex xs12 text-xs-center mb-3>
    <h1 class="display-2 font-weight-light">{{ title }}</h1>
  </v-flex>
</template>

<script>
export default {
  name: 'Heading',
  props: {
    title: String
  }
}
</script>
