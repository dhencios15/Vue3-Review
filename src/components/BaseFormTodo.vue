<template>
  <h1 class="text-center my-4 font-bold text-2xl">
    TODO APP
  </h1>
  <form class="text-center flex flex-col space-y-2 justify-center items-center">
    <input
      class="py-1 px-2 rounded-lg outline-none focus-within:ring-2 text-sm"
      type="text"
      placeholder="Add todo.."
    />
    <button
      type="submit"
      class="bg-blue-500 text-gray-200 py-1 px-2 rounded-lg text-xs outline-none focus-within:outline-none hover:text-gray-600 hover:bg-blue-300"
    >
      Add todo
    </button>
  </form>
</template>

<script>
export default {}
</script>

<style></style>
