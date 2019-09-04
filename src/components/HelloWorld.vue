<template>
  <div class="hello">
    helloworld
  </div>
</template>

<script>
import '@assets/js/first.js'
import '@assets/js/second.js'
import '@assets/js/three.js'
export default {
  name: 'HelloWorld',
  data () {
    return {}
  },
  watch: {},
  computed: {},
  methods: {},
  mounted () {}
}
</script>

<style scoped>
@import url('../assets/css/b.css');
@import '../assets/css/a.css';
</style>
