<template>
  <section>
    <h3>{{ title }}</h3>
    <h1>Professional Translation services</h1>
    <p>Quick. Simple. Professional</p>

    <Button text="Translate now!" color="#468499" />
  </section>
</template>

<script>
import Button from './Button';

export default {
  name: 'Section',
  props: {
    title: String,
  },
  components: {
    Button,
  },
};
</script>

<style></style>
