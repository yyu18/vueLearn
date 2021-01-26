<template>
  <div id="app">
    <Todos v-bind:todos="todos" msg='hello'/>
  </div>
</template>

<script>
import Todos from './components/Todos'
export default {
  name: 'App',
  components: {
    Todos
  },
  data() {
    return {
      todos: [
        {
          id:1,
          title:'todo one',
          completed:false
        },
        {
          id:2,
          title:'todo two',
          completed:false
        },
        {
          id:3,
          title:'todo three',
          completed:false
        }
      ]
    }
  }
}
</script>

<style>

</style>