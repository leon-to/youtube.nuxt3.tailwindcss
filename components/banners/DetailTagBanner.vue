<template>
  <!-- component -->
  <!-- https://tailwindcomponents.com/component/tags -->
  <div class="flex items-center text-gray-200 bg-gray-800">
    
    <ul class="flex-1 p-3 space-x-2 ">
      <li 
        class="inline-flex items-center px-3 py-1 text-xs font-bold text-black bg-gray-200 rounded-full leading-sm">
        All
      </li>
      <li v-for="tag in tags" :key="tag"
        class="inline-flex items-center px-3 py-1 text-xs font-bold bg-gray-600 rounded-full leading-sm">
        {{tag}}
      </li>
      <div>
      </div>
    </ul>
    <svg xmlns="http://www.w3.org/2000/svg" class="right-0 flex w-5 h-5" viewBox="0 0 20 20" fill="currentColor">
      <path fill-rule="evenodd"
        d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z"
        clip-rule="evenodd" />
    </svg>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        tags: ['Mixes', 'Music', 'Sitcoms', 'Playlists', "Conan O'Brien"]
      }
    },
    setup() {

    },
  }
</script>