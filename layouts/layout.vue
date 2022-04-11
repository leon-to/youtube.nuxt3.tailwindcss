<template>
  <div class="flex flex-col h-screen text-2xl">
    <navbars-layout-top-navbar class="flex-0 w-screen h-16 bg-blue-500"/>
    <div class="flex flex-row w-full h-full">  
      <navbars-layout-side-navbar class="flex-0 h-full w-44 bg-green-400"/>
      <div class="flex flex-col w-full h-full ">
        <banners-layout-tag-banner class="h-8 bg-yellow-400"/>
        <lists-layout-card-list class="flex-0 h-full w-full bg-red-400"/>
      </div>
    </div>
  </div>
</template>