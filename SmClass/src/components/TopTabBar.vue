<template>
<van-tabs :active="active">
    
  <van-tab v-for="index in 2" :title="'选项 ' + index">
    内容 {{ index }}
  </van-tab>
</van-tabs>
</template>

<script>
export default {
  name: "nav-tab-bar",
  data() {
    return {
      active: 0
    };
  }
};
</script>

<style scoped>

</style>
