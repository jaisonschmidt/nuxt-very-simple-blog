<template>
  <div v-if="post">
    <h1>{{ post.title }}</h1>
    <p>{{ post.content }}</p>
  </div>
  <div v-else>
    <p>Post não encontrado.</p>
  </div>
</template>

<script setup>
import { posts } from '@/data/posts';

const route = useRoute();
const post = posts.find((p) => p.slug === route.params.slug);
</script>
