<template>
  <div id="app">
    <todo-header></todo-header>
    <todo-input></todo-input>
    <todo-list></todo-list>
    <todo-footer></todo-footer>
  </div>
</template>

<script>
// var my_com ={...} 하고 정의할 때의 "컴포넌트 내용"
import TodoHeader from './components/TodoHeader.vue'
import TodoInput from './components/TodoInput.vue'
import TodoList from './components/TodoList.vue'
import TodoFooter from './components/TodoFooter.vue'


export default {
  components:{
    'TodoHeader' : TodoHeader, 
    'TodoInput' :TodoInput,
    'TodoList' : TodoList,
    'TodoFooter' :TodoFooter,
  }
}
</script>

<style>

</style>
