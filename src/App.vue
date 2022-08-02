<template>
  <div>
    <!-- percentage：进度百分比 -->
    <!-- color:进度条颜色 -->
    <!-- stroke-width:进度条宽度 -->
    <Progress percentage="50"></Progress>
    <Progress percentage="20" color="green"></Progress>
    <Progress percentage="20" color="pink" stroke-width="200"></Progress>
  </div>
</template>

<script>
import Progress from "@/components/Progress.vue";
export default {
  components: {
    Progress,
  },
  data() {
    return {};
  },

  created() {},

  methods: {},
};
</script>

<style scoped></style>
