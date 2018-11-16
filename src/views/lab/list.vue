<template>
  <div>
    <h1>this is vue component</h1>
    <p>
      {{ msg }}
    </p>
    <el-button @click="sendPost">post</el-button>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: 'message'
    }
  },
  created () {

  },
  methods: {
    sendPost () {
      console.log('')
    }
  }
}
</script>

<style scoped>
</style>
