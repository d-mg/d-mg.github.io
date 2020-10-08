<template>
  <div class="personal">
    <h3>Dries Goethuys</h3>
    <ul>
      <li>Violetstraat 17</li>
      <li>Tienen, Belgium</li>
      <li><a href="mailto:dries.goethuys@gmail.com">dries.goethuys@gmail.com</a></li>
      <li><a href="tel:+32478703934">+32478 70 39 34</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'PersonalInfo'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.personal {
  margin: 0 10em;
  text-align: left;
}
ul {
  list-style-type: none;
}
</style>
