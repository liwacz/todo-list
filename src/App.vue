<template>
  <div id="app">
    <todo-list />
    <new-todo />
    <todo-summary />
  </div>
</template>

<script>
import TodoSummary from './components/TodoSummary.vue'
import TodoList from './components/TodoList.vue'
import NewTodo from './components/NewTodo.vue'

export default {
  name: 'app',
  components: {
    TodoList,
    NewTodo,
    TodoSummary
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
