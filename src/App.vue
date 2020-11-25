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
          <h1 class="text-center my-4 font-bold text-2xl">
            TODO APP
          </h1>
          <form
            class="text-center flex flex-col space-y-2 justify-center items-center"
          >
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
          <div class="text-center flex justify-center items-center my-4">
            <ul class="space-y-2 w-1/2">
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
        </div>
      </div>
    </div>
  </div>
</template>

<script setup></script>
