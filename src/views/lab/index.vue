<template>
  <div>
    <el-container>
      <el-header>
        <h1>{{ msg }}</h1>
      </el-header>
      <el-container>
        <el-aside style="width: 25%">
          <router-view name="asideMenu"></router-view>
        </el-aside>
        <el-main>
          <router-view></router-view>
        </el-main>
      </el-container>
    </el-container>
  </div>
</template>

<script>
export default {
  name: 'Lab',
  data () {
    return {
      msg: 'This is Lab root'
    }
  }
}
</script>
