<template>
  <body>
    <div class="wrapper">
      <headerMainTheme />
      <mainTheme />
      <underMainTheme/>
      <upperFooter />
      <bottomFooter />
    </div>
  </body>
</template>

<script>
import mainTheme from './components/mainTheme.vue'
import headerMainTheme from './components/headerMainTheme.vue'
import underMainTheme from './components/underMainTheme.vue'
import upperFooter from './components/upperFooter.vue'
import bottomFooter from './components/bottomFooter.vue'


export default {
  name: 'App',
  components: {
    mainTheme,
    headerMainTheme,
    underMainTheme,
    upperFooter,
    bottomFooter
  }
}
</script>

<style>
body {
  margin: 0;
}

.wrapper {
  width: 100%;
  margin: 0 auto;
}
</style>
