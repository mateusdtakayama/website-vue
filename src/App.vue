<template>
  <div id="app">
    <HeaderView></HeaderView>
  </div>
</template>

<script>
import './styles/global.css'

import HeaderView from './components/HeaderView.vue'

export default {
  name: 'App',
  components: {
    HeaderView,
  }
}
</script>
