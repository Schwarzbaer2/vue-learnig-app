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

<script>
export default {
  props: ['resources']
};
</script>
