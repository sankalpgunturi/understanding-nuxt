<template>
  <div>
    <h1>Blog Post</h1>
    <p>This is a blog post</p>
    <p>Post ID: {{ route.params.id }}</p>
  </div>
</template>

<script setup>
const route = useRoute();
</script>
