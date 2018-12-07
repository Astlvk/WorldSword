<template>
  <div>
    <h1>this is vue component</h1>
    <p>
      {{ msg }}
    </p>
    <el-table :model="list">
      <el-table-column label="Name" prop="name" align="center" min-width="100"></el-table-column>
      <el-table-column label="Cd" prop="cd" align="center" min-width="100"></el-table-column>
    </el-table>
    <br />
    <el-button @click="sendPost">post</el-button>
  </div>
</template>

<script>
export default {
  data () {
    return {
      list: [],
      msg: 'message'
    }
  },
  created () {
    console.log('axios...? ')
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
