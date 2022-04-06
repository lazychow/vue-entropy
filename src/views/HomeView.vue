<template>
  <el-container>
    <el-aside width="200px">Aside</el-aside>
    <el-container>
      <!-- <el-header>Header</el-header>
      <el-main>Main</el-main>
      <el-footer>Footer</el-footer> -->
      <el-form label-position="right" style="width: 500px" label-width="100px">
        <el-form-item label="aaaa">
          <el-input size="mini" />
        </el-form-item>
        <el-form-item label="bbbb">
          <el-input size="mini" />
        </el-form-item>
      </el-form>
    </el-container>
  </el-container>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'HomeView',
  components: {},
})
</script>
