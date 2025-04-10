<template>
  <div>
    <NuxtLink :to="`/post/${post.slug}`">
      <h2>{{ post.title }}</h2>
    </NuxtLink>
    <p>{{ post.description }}</p>
    <hr />
  </div>
</template>

<script setup>
defineProps({ post: Object });
</script>
