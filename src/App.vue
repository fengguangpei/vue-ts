<script setup lang="ts">
</script>

<template>
  <div class="count">
    <div class="header">
      This is Header
    </div>
    <div class="main">
      This is Main
    </div>
    <div class="footer">
      This is Footer
    </div>
  </div>
</template>

<style scoped>
.count {
  height: 100vh;
  width: 100vw;
  display: flex;
  flex-direction: column;

  .header {
    height: 100px;
    border-bottom: 1px solid #ccc;
    text-align: center;
    vertical-align: middle;
  }

  .main {
    flex: 1;
    text-align: center;
    vertical-align: middle;
  }

  .footer {
    border-top: 1px solid #ccc;
    height: 100px;
    text-align: center;
    vertical-align: middle;
  }
}
</style>
