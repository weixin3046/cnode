<template>
  <div>
    <node-header></node-header>
  </div>
</template>

<script>
import nodeHeader from './header.vue'
export default {
  name: 'home',
  data () {
    return {
      msg: 'Hello world'
    }
  },
  components:{nodeHeader},
  methods: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
