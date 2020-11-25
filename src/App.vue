<template>
  <div class="bg-gray-900 min-h-screen font-nerko">
    <div class="container mx-auto p-20 h-screen">
      <div class="relative w-full">
        <div
          class="absolute inset-x-0 top-0 mx-auto bg-gray-300 border w-1/2 h-96 rounded-lg shadow-lg transform rotate-4"
        />
        <div
          class="absolute inset-x-0 top-0 mx-auto bg-gray-300 border w-1/2 h-96 rounded-lg shadow-lg transform -rotate-4"
        />
        <div
          class="absolute inset-x-0 top-0 mx-auto bg-gray-300 border w-1/2 h-96 rounded-lg shadow-lg"
        >
          <BaseFormTodo />
          <ListOfTodos />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import ListOfTodos from './components/ListOfTodos'
import BaseFormTodo from './components/BaseFormTodo'

export default {
  components: { ListOfTodos, BaseFormTodo }
}
</script>
