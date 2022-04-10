<template>
  <!-- component -->
  <!-- https://tailwindcomponents.com/component/tags -->
  <div class="flex items-center text-gray-200 bg-[#202020] border-y border-[#545454] px-4">

    <ul class="flex-1 p-3 space-x-3">
      <li class="inline-flex items-center px-3 py-1 text-sm  text-black bg-gray-200 rounded-full leading-sm">
        All
      </li>
      <li v-for="tag in tags" :key="tag"
        class="inline-flex items-center px-3 py-1 text-sm bg-[#363636] border border-[#545454] rounded-full leading-sm ">
        {{tag}}
      </li>
      <div>
      </div>
    </ul>
    <!-- <svg xmlns="http://www.w3.org/2000/svg" class="right-0 flex w-5 h-5 fill-[#545454]" viewBox="0 0 20 20" fill="currentColor">
      <path fill-rule="evenodd"
        d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z"
        clip-rule="evenodd" />
    </svg> -->
    <div class="flex w-4 h-4">
      <svg viewBox="0 0 16 16" preserveAspectRatio="xMidYMid meet" focusable="false" class="style-scope yt-icon fill-[#fafafa] ">
        <g mirror-in-rtl="" class="style-scope yt-icon">
          <path d="M4.97,12.65L9.62,8L4.97,3.35l0.71-0.71L11.03,8l-5.35,5.35L4.97,12.65z" class="style-scope yt-icon">
          </path>
        </g>
      </svg>
    </div>
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