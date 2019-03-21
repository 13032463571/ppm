<template>
    <div id="firstcomponent" >
      <H1 v-bind:class="[myClass]">I'm a title</H1>
      <a>written by {{author}}</a>
    </div>
</template>

<script type="text/javascript">
export default {
  data () {
    return {
      author: '王震',
      myClass: 'testClass'
    }
  }
}
</script>

<style scoped>
  .testClass{
    color: blue;
  }
</style>
