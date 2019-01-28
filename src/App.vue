<template>
  <!-- v-app needed for layout -> https://vuetifyjs.com/en/framework/default-markup -->
  <v-app>
    <Nav></Nav>

    <v-content>
      <Login/>
    </v-content>
  </v-app>
</template>

<script>
    import Test from './components/Test'
    import Login from './components/Login'
    import Nav from './components/Nav'

export default {
  name: 'App',
  components: {
    Test, Login, Nav
  },
  data () {
    return {
      //
    }
  }
}
</script>
