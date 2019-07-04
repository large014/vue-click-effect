<template>
  <div id="app">
      <div class="rippletest">
          <Ripple ref="ripple1" circleC="rgba(50,220,40,0.5)"/>
          rippleEffect Test
      </div>
      <div class="rippletest">
          <Ripple ref="ripple2" circleC="rgba(10,120,140,0.2)"/>
          rippleEffect Test
      </div>
  </div>
</template>

<script>
import Ripple from './components/Ripple.vue'
export default {
  name: 'app',
  components: {
    Ripple
  },
  methods: {
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.rippletest{
  width: 200px;
  height: 100px;
  border: 1px solid #CCC;
  position: relative;
}

</style>
