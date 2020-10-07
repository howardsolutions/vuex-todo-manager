<template>
  <div id="app">
      <div class="container">
      <h1> The Thinh Phung's Todo Manager App</h1>
        <AddToDo />
        <FilterTodo />
        <Todos />
      </div>
  </div>
</template>

<script>
import Todos from "./components/Todos"
import AddToDo from "./components/AddToDo"
import FilterTodo from "./components/FilterTodo"

export default {
  name: 'App',
  components: {
    Todos,
    AddToDo,
    FilterTodo
  }
}
</script>

<style>
  body {
    font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
    line-height: 1.6;
    background: #e8f7f0;
  }

  .container {
    max-width: 1100px;
    margin: auto;
    overflow: auto;
    padding: 0 2rem;
  }

  .container h1 {
    text-align: center;
  }
</style>
