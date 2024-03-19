<template>
  <div>
    <h1>About</h1>
    <p>This is the about page</p>
    <div>
      <button @click="enableCustomLayout">Update layout</button>
    </div>
  </div>
</template>

<script setup lang="ts">
// definePageMeta({
//   layout: 'another',
// });

function enableCustomLayout() {
  setPageLayout('another');
}
</script>
