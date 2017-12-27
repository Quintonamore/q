<template>
  <div class="hello">
    <h1>{{name}}</h1>
    <p>
      I'm a Software Engineer living in Seattle. Currently I smash bugs and develop cool applications as a
      Full Stack Engineer at <a href='https://www.bargreen.com'>Bargreen Ellingson</a>.
    </p>
    <p>
      When I'm not developing software I enjoy spending money on stamps I don't need, watching the Spurs demolish the Warriors in the 2018 semi-finals,
      and reading.
    </p>
    <h3>Programming Skills</h3>
    <ul>
      <li>Languages: Java, JavaScript, Python, C++, HTML, CSS</li><br>
      <li>Frameworks: Angular 2, VueJS, Flask, Qt</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
      name: 'Quinton Teas'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: circle;
  padding: 0;
}
li {
  display: list-item;
  list-style-type: circle;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
