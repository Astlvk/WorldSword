<template>
  <div>
    <h1>this is vue component</h1>
    <p>
      {{ msg }}
    </p>
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: 'message'
    }
  }
}
</script>

<style scoped>
</style>
