<template>
  <div class='hello'>
    <HelloWorld msg="vue3 in vite" />
  </div>
</template>

<script lang="ts">
import HelloWorld from '../components/HelloWorld.vue'
export default {
  name: 'hello',
  data() {
    return {}
  },
  //静态
  props: {},
  computed: {},
  //部件
  components: { HelloWorld },
  //监听
  watch: {},
  //方法表示一个具体的操作，主要书写业务逻辑；
  methods: {},
  created() {},
}
</script>

<style scoped>
</style>
