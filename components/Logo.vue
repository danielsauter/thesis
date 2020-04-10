<template>
  <div>
    <el-row>
      <el-button>Default</el-button>
      <el-button type="primary">Primary</el-button>
      <el-button type="success">Success</el-button>
      <el-button type="info">Info</el-button>
      <el-button type="warning">Warning</el-button>
    </el-row>

    <el-row>
      <el-button plain>Plain</el-button>
      <el-button type="primary" plain>Primary</el-button>
      <el-button type="success" plain>Success</el-button>
      <el-button type="info" plain>Info</el-button>
      <el-button type="warning" plain>Warning</el-button>
    </el-row>
    <svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
      <path d="M 10,30
              A 20,20 0,0,1 50,30
              A 20,20 0,0,1 90,30
              Q 90,60 50,90
              Q 10,60 10,30 z"/>
    </svg>
  </div>
</template>
<style>
.NuxtLogo {
  animation: 1s appear;
  margin: auto;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
</style>
