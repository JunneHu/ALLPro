<template>
  <div class="m-header">
    <el-row>
      <el-col :span="5">
        <geo />
      </el-col>
      <el-col :span="5">
        <User />
      </el-col>
      <el-col :span="14">
        <nav-bar />
      </el-col>
    </el-row>
  </div>
</template>
<script>
  import Geo from './geo.vue'
  import User from './user.vue'
  import NavBar from './nav.vue'

  export default {
    components: {
      Geo,
      User,
      NavBar
    }
  }

</script>

<style lang="scss">

</style>
