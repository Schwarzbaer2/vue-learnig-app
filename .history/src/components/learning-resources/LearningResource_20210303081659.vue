<template>
  <li>
    <div>
      <header>
        <h3>{{ title }}</h3>
        <butto>Delete</butto>
      </header>
    </div>
    <p></p>
    <nav>
      <a href="">View Resource</a>
    </nav>
  </li>
</template>

<script>
export default {
  props: ['title', 'description', 'link']
};
</script>
