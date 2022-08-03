<template>
  <br-input
    label="name"
    placeholder="Digite seu nome"
    id="name"
    :value="name"
    @input="name = $event.target.value"
  ></br-input>
  <p>Teste: {{ name }}</p>
</template>

<script>
import CustomModelDirective from './custom-model';
import '@govbr-ds/webcomponents/dist/webcomponents.umd.min.js';

export default {
  name: 'Input',
  data() {
    return {
      name: 'Marcelo Silva',
    };
  },
  directives: {
    CustomModelDirective,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
