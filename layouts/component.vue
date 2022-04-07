<template>
  <div class="flex flex-col h-screen">
    <navbars-component-top-navbar/>
    <div class="flex flex-row w-full h-full">  
      <navbars-component-side-navbar/>
      <div class="flex flex-col w-full h-full">
        <banners-component-tag-banner/>
        <lists-component-card-list class="flex-0 h-full w-full bg-red-400"/>
      </div>
    </div>
  </div>
</template>