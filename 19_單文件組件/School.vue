<template>
  <div class="demo">
    <h2>學校名稱：{{ name }}</h2>
    <h2>學校地址：{{ address }}</h2>
    <button @click="showName">點我提示學校名</button>
  </div>
</template>

<script>
export default {
  name: "School",
  data() {
    return {
      name: "銀輝",
      address: "台北大安",
    };
  },
  methods: {
    showName() {
      alert(this.name);
    },
  },
};
</script>

<style>
.demo {
  background-color: orange;
}
</style>
