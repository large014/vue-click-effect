# vue-click-effect
ボタンエフェクト  
[DEMO](https://large014.github.io/vue-click-effect/)
## Install
```
./src/components/Ripple.vue をコピー
```

### Usage
```
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

<template>
  <div id="app">
      <div class="rippletest">
          <Ripple ref="ripple1" circleC="rgba(50,220,40,0.5)"/>
          rippleEffect Test
      </div>
  </div>
</template>
```
プロパティ  
[circleC] エフェクトの色を設定 rgba()形式

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
