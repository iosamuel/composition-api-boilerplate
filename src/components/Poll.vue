<script setup></script>

<template>
  <div class="w-96 mx-auto p-5 flex flex-col items-center">
    <div class="w-full flex flex-col gap-2 p-5 bg-slate-600 text-white rounded">
      <h2 class="text-2xl">Poll Title</h2>
      <ul class="w-72 mx-auto">
        <li class="border p-2 relative">
          <span class="block w-2/3 break-words">Option 1</span>
          <span class="absolute top-0 right-0 p-2"> (2 votes) </span>
          <div class="mt-2 text-sm">
            <button
              class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-xs px-2 py-1 mr-1 focus:outline-none"
              type="button"
            >
              Vote
            </button>
            <button
              class="focus:outline-none text-white bg-red-700 hover:bg-red-800 focus:ring-4 focus:ring-red-300 font-medium rounded-lg text-xs px-2 py-1"
              type="button"
            >
              Remove
            </button>
          </div>
        </li>
      </ul>
    </div>
    <form class="w-full p-2 flex flex-col">
      <label for="option" class="block mb-2 text-sm font-medium text-gray-900">
        Add an option
      </label>
      <input
        type="text"
        id="option"
        class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5"
      />
      <button
        type="button"
        class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm w-full sm:w-auto px-5 py-2.5 text-center"
      >
        Add
      </button>
    </form>
  </div>
</template>
