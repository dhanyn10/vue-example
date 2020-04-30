<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" id="vue-logo">
    <b-container>
      <Form/>
      <Button/>
    </b-container>
  </div>
</template>

<script>
import Vue from 'vue'

//apps components
import Button from './components/Button.vue'
import Form from './components/Form.vue'

//bootstrap components
import {BContainer} from 'bootstrap-vue'

Vue.component('b-container', BContainer)

export default {
  name: 'App',
  components: {
    Button,
    Form
  }
}
</script>

<style>
#vue-logo{
  display: block;
  margin: 0 auto;
}
</style>
