<script setup>
import { ref } from 'vue';

const image_paths = [
    "./result/exp1.png",
    "./result/exp2.png",
    "./result/exp3.png",
  ]
</script>

<template>
  <div>
    <el-divider />

    <el-row justify="center">
      <h1 class="section-title">More Results</h1>
    </el-row>

    <el-row justify="center">
      <el-col :span="14">
        <img :src=image_paths[0] style="width: 100%; margin-bottom: 50px;">
      </el-col>
      <el-col :span="14">
        <img :src=image_paths[1] style="width: 100%; margin-bottom: 50px;">
      </el-col>
      <el-col :span="14">
        <img :src=image_paths[2] style="width: 100%; margin-bottom: 50px;">
      </el-col>
    </el-row>

  </div>
</template>

<style scoped>
.el-row {
  margin-bottom: 20px;
}
.el-row:last-child {
  margin-bottom: 0;
}
.el-col {
  border-radius: 4px;
}

.grid-content {
  border-radius: 4px;
  min-height: 36px;
  background: black;
}
</style>