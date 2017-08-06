<template>
  <div class="hello">
    <h1>Arturo Manzaneda</h1>
    <h2>Welcome to my personal site</h2>
    <h3>Currently learning:</h3>
    <ul>
      <li><a href="https://vuejs.org/" target="_blank" rel="noopener">Vue JS</a></li>
      <li><a href="https://developers.google.com/web/progressive-web-apps/" target="_blank" rel="noopener">PWA - Progressive Web Apps</a></li>
    </ul>
    <h3>Right now focused working with the following awesome things:</h3>
    <ul>
      <li><a href="https://projects.spring.io/spring-boot/" target="_blank" rel="noopener">Spring Boot</a></li>
      <li><a href="https://www.corda.net/" target="_blank" rel="noopener">Corda - Distributed Ledger</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'hello'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #35495E;
}
</style>
