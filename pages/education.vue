<template>
  <div class="education-container">
    <div>
      <h1 style="text-align: center;">Education</h1>
      <Card
        title="Internet Applications and web developer"
        content="Fanshawe College, London, ON, Canada"
        year="2014-2015"
      />
      <Card
        title="Master of Science (Information Technology)"
        content="Sardar Patel University, VallabhVidhyanagar, Gujarat, India"
        year="2011-2013"
      />
      <Card
        title="Bachelors of Computer Applications"
        content="Sardar Patel University, VallabhVidhyanagar, Gujarat, India"
        year="2008-2011"
      />
    </div>
  </div>
</template>

<script>
import Card from '../components/Card';
export default {
  components: {
    Card,
  },
};
</script>
