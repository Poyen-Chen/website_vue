<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      oooooooooooooooooooxxxxxxxxxxxxxxxxxxxx
    </p>
    <h3>Social Media</h3>
    <ul>
      <li><a href="https://www.instagram.com/samjanity996/" target="_blank" rel="noopener">Intagram</a></li>
      <li><a href="https://twitter.com/sam960628" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://github.com/Poyen-Chen" target="_blank" rel="noopener">Github</a></li>
      <li><a href="https://www.facebook.com/profile.php?id=100003520862258" target="_blank" rel="noopener">Facebook</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
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
  color: #42b983;
}
</style>
