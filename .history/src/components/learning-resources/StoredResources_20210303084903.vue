<template>
  <ul>
    <LearningResource
      v-for="res in resources"
      :key="res.id"
      :title="res.title"
      :description="res.description"
      :link="res.link"
    /></ul
></template>

import LearningResource from './LearningResource.vue';

<script>
export default {
  props: ['resources'],
  components: { LearningResource }
};
</script>
