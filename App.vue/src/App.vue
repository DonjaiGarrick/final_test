<template>
  <div class="container">
    <h1>{{ studentName }}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      studentName: "นายดลใจ สุดจริง" // แก้ไขเป็นชื่อ-นามสกุลของคุณเอง
    };
  },
};
</script>

<style>
.container {
  width: 100vw;
  height: 100vh;
  background-color: skyblue;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>