<template>
  <div class="progress_box" :style="{ width: strokeWidth + 'px' }">
    <div
      class="progress_content"
      :style="{ width: percentage + '%', backgroundColor: color }"
    ></div>
  </div>
</template>

<script>
export default {
  props: {
    percentage: {
      type: String,
      required: true,
    },
    color: {
      type: String,
      default: "red",
    },
    strokeWidth: {
      type: String,
      default: '400',
    },
  },
  data() {
    return {};
  },

  created() {},

  methods: {},
};
</script>

<style scoped lang="less">
.progress_box {
  width: 400px;
  height: 10px;
  border-radius: 10px;
  margin: 15px;
  background-color: #ccc;
  .progress_content {
    width: 20%;
    height: 10px;
    border-radius: 10px;
    background-color: red;
  }
}
</style>
