<template>
  <div> {{msg}}</div>
</template>

<script>
export default {
  name: 'hello',
  props: {
    msg: {
      type: String,
      default: ''
    }
  },
  data () {
    return {
    }
  },
  methods: {}
}
</script>

<style lang='scss' scoped>

</style>
