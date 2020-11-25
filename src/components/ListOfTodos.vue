<template>
  <div class="text-center flex justify-center items-center my-4">
    <ul class="space-y-2 w-1/2 overflow-y-auto h-56 px-2">
      <li
        class="py-1 px-2 rounded-lg shadow-lg bg-white text-sm flex items-center hover:bg-gray-200 w-full"
      >
        <button
          class="mr-2 w-4 text-xs rounded-full bg-green-500 shadow-lg text-white flex items-center justify-center hover:bg-green-300 hover:text-green-600"
        >
          /
        </button>
        <div class="flex-grow flex justify-between items-center">
          <h1>TODO</h1>
        </div>
        <button
          class="w-4 text-xs rounded-full bg-red-500 shadow-lg text-white flex items-center justify-center hover:bg-red-300 hover:text-red-600"
        >
          x
        </button>
      </li>
    </ul>
  </div>
</template>

<script>
export default {}
</script>

<style></style>
