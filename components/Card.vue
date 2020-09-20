<template>
  <div class="card">
    <div class="header-title">
      <span>{{ title }}</span>
      <span class="year">{{ year }}</span>
    </div>
    <div class="location">
      <span>{{ location }}</span>
    </div>
    <div class="content">
      <span>{{ content }}</span>
    </div>
    <div v-if="tags.length > 0 && tags[0] != ''" class="tags">
      <span v-for="(tag, x) in tags" :key="x">
        {{ tag }}
      </span>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Card',
  props: {
    title: {
      type: String,
      default: '',
    },
    location: {
      type: String,
      default: '',
    },
    year: {
      type: String,
      default: '',
    },
    content: {
      type: String,
      default: '',
    },
    tagstring: {
      type: String,
      default: '',
    },
  },
  computed: {
    tags() {
      return this.tagstring.toString().split(',');
    },
  },
};
</script>
