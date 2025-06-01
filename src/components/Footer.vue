<script lang="ts" setup>
</script>

<template>
  
  <div class="bg">
    
    <el-watermark :content="['Emotion-Director']" :gap="['60','0']" :z-index="0">
      <el-row justify="center">
        <p class="footer">
          Anonymous NeurIPS 2025 Submission
        </p>
      </el-row>
    </el-watermark>
  </div>
</template>

<style scoped>

/* 页脚背景 */
.bg {
  background-color: rgb(235, 235, 235);
}

/* 页脚文字 */
.footer {
  text-align: center;
  margin: 20px;
  z-index: 1;
}

</style>