<template>
  <div>
    <button @click="enableCustomLayout">Update layout</button>
  </div>
</template>

<script setup>
const route = useRoute()
function enableCustomLayout () {
  route.meta.layout = "layout"
}
definePageMeta({
  layout: false,
});
</script>
