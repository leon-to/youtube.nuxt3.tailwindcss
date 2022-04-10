<template>

  <aside class="w-72 h-full bg-[#202020]" aria-label="Sidebar">
    <div class="pr-3 py-3 overflow-y-auto ">
      <ul class="">
        <li>
          <a href="#" class="flex items-center py-2 pl-5 text-sm font-normal text-white bg-[#363636]">
            <svg class="w-6 h-6 fill-white" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
              <g>
                <path d="M4,10V21h6V15h4v6h6V10L12,3Z"></path>
              </g>
            </svg>
            <span class="ml-5">Home</span>
          </a>
        </li>
        <li>
          <a href="#" class="flex items-center py-2 pl-5 text-sm font-normal  text-white  hover:bg-[#363636]">
            <svg class="w-6 h-6 fill-white" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
              <g class="style-scope yt-icon">
                <path
                  d="M9.8,9.8l-3.83,8.23l8.23-3.83l3.83-8.23L9.8,9.8z M13.08,12.77c-0.21,0.29-0.51,0.48-0.86,0.54 c-0.07,0.01-0.15,0.02-0.22,0.02c-0.28,0-0.54-0.08-0.77-0.25c-0.29-0.21-0.48-0.51-0.54-0.86c-0.06-0.35,0.02-0.71,0.23-0.99 c0.21-0.29,0.51-0.48,0.86-0.54c0.35-0.06,0.7,0.02,0.99,0.23c0.29,0.21,0.48,0.51,0.54,0.86C13.37,12.13,13.29,12.48,13.08,12.77z M12,3c4.96,0,9,4.04,9,9s-4.04,9-9,9s-9-4.04-9-9S7.04,3,12,3 M12,2C6.48,2,2,6.48,2,12s4.48,10,10,10s10-4.48,10-10S17.52,2,12,2 L12,2z"
                  class="style-scope yt-icon"></path>
              </g>
            </svg>
            <span class="flex-1 ml-5 whitespace-nowrap">Explore</span>
          </a>
        </li>
        <li>
          <a href="#" class="flex items-center py-2 pl-5 text-sm font-normal   text-white  hover:bg-[#363636]">
            <svg class="w-6 h-6 fill-white" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
              <g height="24" viewBox="0 0 24 24" width="24" class="style-scope yt-icon">
                <path
                  d="M10 14.65v-5.3L15 12l-5 2.65zm7.77-4.33c-.77-.32-1.2-.5-1.2-.5L18 9.06c1.84-.96 2.53-3.23 1.56-5.06s-3.24-2.53-5.07-1.56L6 6.94c-1.29.68-2.07 2.04-2 3.49.07 1.42.93 2.67 2.22 3.25.03.01 1.2.5 1.2.5L6 14.93c-1.83.97-2.53 3.24-1.56 5.07.97 1.83 3.24 2.53 5.07 1.56l8.5-4.5c1.29-.68 2.06-2.04 1.99-3.49-.07-1.42-.94-2.68-2.23-3.25zm-.23 5.86l-8.5 4.5c-1.34.71-3.01.2-3.72-1.14-.71-1.34-.2-3.01 1.14-3.72l2.04-1.08v-1.21l-.69-.28-1.11-.46c-.99-.41-1.65-1.35-1.7-2.41-.05-1.06.52-2.06 1.46-2.56l8.5-4.5c1.34-.71 3.01-.2 3.72 1.14.71 1.34.2 3.01-1.14 3.72L15.5 9.26v1.21l1.8.74c.99.41 1.65 1.35 1.7 2.41.05 1.06-.52 2.06-1.46 2.56z"
                  class="style-scope yt-icon"></path>
              </g>
            </svg>
            <span class="flex-1 ml-5 whitespace-nowrap">Shorts</span>
          </a>
        </li>
        <li>
          <a href="#" class="flex items-center py-2 pl-5 text-sm font-normal  text-white hover:bg-[#363636]">
            <svg class="w-6 h-6 fill-white" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
              <g class="style-scope yt-icon">
                <path d="M10,18v-6l5,3L10,18z M17,3H7v1h10V3z M20,6H4v1h16V6z M22,9H2v12h20V9z M3,10h18v10H3V10z"
                  class="style-scope yt-icon"></path>
              </g>
            </svg>
            <span class="flex-1 ml-5 whitespace-nowrap">Subscriptions</span>
          </a>
        </li>
      </ul>
      <ul class="pt-4 mt-4  border-t  border-[#363636]">
        <li>
          <a href="#"
            class="flex items-center py-2 pl-5 text-sm font-normal  transition duration-75   hover:bg-[#363636] text-white group">
            <svg class="w-6 h-6 fill-white" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
              <g class="style-scope yt-icon">
                <path d="M11,7l6,3.5L11,14V7L11,7z M18,20H4V6H3v15h15V20z M21,18H6V3h15V18z M7,17h13V4H7V17z"
                  class="style-scope yt-icon"></path>
              </g>
            </svg>
            <span class="ml-5">Library</span>
          </a>
        </li>
        <li>
          <a href="#"
            class="flex items-center py-2 pl-5 text-sm font-normal  transition duration-75   hover:bg-[#363636] text-white group">
            <svg class="w-6 h-6 fill-white" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
              <g class="style-scope yt-icon">
                <path
                  d="M14.97,16.95L10,13.87V7h2v5.76l4.03,2.49L14.97,16.95z M22,12c0,5.51-4.49,10-10,10S2,17.51,2,12h1c0,4.96,4.04,9,9,9 s9-4.04,9-9s-4.04-9-9-9C8.81,3,5.92,4.64,4.28,7.38C4.17,7.56,4.06,7.75,3.97,7.94C3.96,7.96,3.95,7.98,3.94,8H8v1H1.96V3h1v4.74 C3,7.65,3.03,7.57,3.07,7.49C3.18,7.27,3.3,7.07,3.42,6.86C5.22,3.86,8.51,2,12,2C17.51,2,22,6.49,22,12z"
                  class="style-scope yt-icon"></path>
              </g>
            </svg>
            <span class="ml-5">History</span>
          </a>
        </li>
        <li>
          <a href="#"
            class="flex items-center py-2 pl-5 text-sm font-normal  transition duration-75   hover:bg-[#363636] text-white group">
            <svg class="w-6 h-6 fill-white" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
              <g class="style-scope yt-icon">
                <path d="M10,8l6,4l-6,4V8L10,8z M21,3v18H3V3H21z M20,4H4v16h16V4z" class="style-scope yt-icon"></path>
              </g>
            </svg>
            <span class="ml-5">Your videos</span>
          </a>
        </li>
        <li>
          <a href="#"
            class="flex items-center py-2 pl-5 text-sm font-normal  transition duration-75   hover:bg-[#363636] text-white group">
            <svg class="w-6 h-6 fill-white" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
              <g class="style-scope yt-icon">
                <path
                  d="M14.97,16.95L10,13.87V7h2v5.76l4.03,2.49L14.97,16.95z M12,3c-4.96,0-9,4.04-9,9s4.04,9,9,9s9-4.04,9-9S16.96,3,12,3 M12,2c5.52,0,10,4.48,10,10s-4.48,10-10,10S2,17.52,2,12S6.48,2,12,2L12,2z"
                  class="style-scope yt-icon"></path>
              </g>
            </svg>
            <span class="ml-5">Watch later</span>
          </a>
        </li>
        <li>
          <a href="#"
            class="flex items-center py-2 pl-5 text-sm font-normal  transition duration-75   hover:bg-[#363636] text-white group">
            <svg class="w-6 h-6 fill-white" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
              <g class="style-scope yt-icon">
                <path
                  d="M8,7c0,0.55-0.45,1-1,1S6,7.55,6,7c0-0.55,0.45-1,1-1S8,6.45,8,7z M7,16c-0.55,0-1,0.45-1,1c0,0.55,0.45,1,1,1s1-0.45,1-1 C8,16.45,7.55,16,7,16z M10.79,8.23L21,18.44V20h-3.27l-5.76-5.76l-1.27,1.27C10.89,15.97,11,16.47,11,17c0,2.21-1.79,4-4,4 c-2.21,0-4-1.79-4-4c0-2.21,1.79-4,4-4c0.42,0,0.81,0.08,1.19,0.2l1.37-1.37l-1.11-1.11C8,10.89,7.51,11,7,11c-2.21,0-4-1.79-4-4 c0-2.21,1.79-4,4-4c2.21,0,4,1.79,4,4C11,7.43,10.91,7.84,10.79,8.23z M10.08,8.94L9.65,8.5l0.19-0.58C9.95,7.58,10,7.28,10,7 c0-1.65-1.35-3-3-3S4,5.35,4,7c0,1.65,1.35,3,3,3c0.36,0,0.73-0.07,1.09-0.21L8.7,9.55l0.46,0.46l1.11,1.11l0.71,0.71l-0.71,0.71 L8.9,13.91l-0.43,0.43l-0.58-0.18C7.55,14.05,7.27,14,7,14c-1.65,0-3,1.35-3,3c0,1.65,1.35,3,3,3s3-1.35,3-3 c0-0.38-0.07-0.75-0.22-1.12l-0.25-0.61L10,14.8l1.27-1.27l0.71-0.71l0.71,0.71L18.15,19H20v-0.15L10.08,8.94z M17.73,4H21v1.56 l-5.52,5.52l-2.41-2.41L17.73,4z M18.15,5l-3.67,3.67l1,1L20,5.15V5H18.15z"
                  class="style-scope yt-icon"></path>
              </g>
            </svg>
            <span class="ml-5">Your clips</span>
          </a>
        </li>
        <li>
          <a href="#"
            class="flex items-center py-2 pl-5 text-sm font-normal  transition duration-75   hover:bg-[#363636] text-white group">
            <svg class="w-6 h-6 fill-white" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
              <g class="style-scope yt-icon">
                <path d="M12,15.7L5.6,9.4l0.7-0.7l5.6,5.6l5.6-5.6l0.7,0.7L12,15.7z" class="style-scope yt-icon"></path>
              </g>
            </svg>
            <span class="ml-5">Show more</span>
          </a>
        </li>

      </ul>


      <ul class="mt-4  border-t  border-[#363636]">
        <li
          class="flex items-center pl-5 pt-3 text-sm font-medium text-[#8a8a8a]  transition duration-75   hover:bg-[#363636] group">
          SUBSCRIPTIONS</li>
        <li>
          <a href="#"
            class="flex items-center py-2 pl-5 text-sm font-normal  transition duration-75   hover:bg-[#363636] text-white group">

            <button type="button" class="flex rounded-full">
              <img class="w-6 h-6 rounded-full" src="~/assets/img/day-trading-radio.jpg" alt="user photo">
            </button>

            <span class="ml-5 flex-1">Day Trading Radio</span>
            <svg class="w-4 h-4 fill-[#f80000]" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
              <g class="style-scope yt-icon">
                <path
                  d="M14,12c0,1.1-0.9,2-2,2s-2-0.9-2-2s0.9-2,2-2S14,10.9,14,12z M8.48,8.45L7.77,7.75C6.68,8.83,6,10.34,6,12 s0.68,3.17,1.77,4.25l0.71-0.71C7.57,14.64,7,13.39,7,12S7.57,9.36,8.48,8.45z M16.23,7.75l-0.71,0.71C16.43,9.36,17,10.61,17,12 s-0.57,2.64-1.48,3.55l0.71,0.71C17.32,15.17,18,13.66,18,12S17.32,8.83,16.23,7.75z M5.65,5.63L4.95,4.92C3.13,6.73,2,9.24,2,12 s1.13,5.27,2.95,7.08l0.71-0.71C4.02,16.74,3,14.49,3,12S4.02,7.26,5.65,5.63z M19.05,4.92l-0.71,0.71C19.98,7.26,21,9.51,21,12 s-1.02,4.74-2.65,6.37l0.71,0.71C20.87,17.27,22,14.76,22,12S20.87,6.73,19.05,4.92z"
                  class="style-scope yt-icon"></path>
              </g>
            </svg>
          </a>
        </li>
        <li>
          <a href="#"
            class="flex items-center py-2 pl-5 text-sm font-normal  transition duration-75   hover:bg-[#363636] text-white group">
            <button type="button" class="flex rounded-full">
              <img class="w-6 h-6 rounded-full" src="~/assets/img/teamcoco.jpg" alt="user photo">
            </button>
            <span class="ml-5 flex-1">Team Coco</span>
            <span class="mr-1.5 rounded-full h-1 w-1 bg-sky-500"></span>
          </a>
        </li>

        <li>
          <a href="#"
            class="flex items-center py-2 pl-5 text-sm font-normal  transition duration-75   hover:bg-[#363636] text-white group">
            <button type="button" class="flex rounded-full">
              <img class="w-6 h-6 rounded-full" src="~/assets/img/marshmello.jpg" alt="user photo">
            </button>
            <span class="ml-5 flex-1">Marshmello</span>
            <span class="mr-1.5 rounded-full h-1 w-1 bg-sky-500"></span>
          </a>
        </li>
        <li>
          <a href="#"
            class="flex items-center py-2 pl-5 text-sm font-normal  transition duration-75   hover:bg-[#363636] text-white group">
            <button type="button" class="flex rounded-full">
              <img class="w-6 h-6 rounded-full" src="~/assets/img/vice.jpg" alt="user photo">
            </button>
            <span class="ml-5">VICE News</span>
          </a>
        </li>
      </ul>
    </div>
  </aside>

</template>