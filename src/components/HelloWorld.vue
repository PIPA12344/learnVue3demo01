<template>
  <div>
    <a v-bind:[myLabel]="'https://www.baidu.com'">跳转到百度</a>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data() {
    return {
      myLabel: 'href'
    }
  },
  methods: {

  }
}
</script>

<style scoped>

</style>
