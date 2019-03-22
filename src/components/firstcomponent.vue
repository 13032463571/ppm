<template>
    <div id="firstcomponent" >
      <H1 v-bind:class="[myClass]">I'm a title</H1>
      <a>written by {{author}}</a>
      <el-input v-model="input" placeholder="请输入内容"></el-input>
    </div>
</template>

<script type="text/javascript">
export default {
  data () {
    return {
      author: '王震',
      myClass: 'testClass',
      input: 'ElementUI'
    }
  }
}
</script>

<style scoped>
  .testClass{
    color: blue;
  }
</style>
