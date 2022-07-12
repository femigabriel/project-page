<template>
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/line-awesome/1.3.0/line-awesome/css/line-awesome.min.css"
  />
  <link href="open-sans.css" rel="stylesheet" type="text/css" />

  <Header />

  <HelloWorld />
  <Form />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Header from "./components/Header.vue";
import Form from "./components/Form.vue";

export default {
  name: "App",
  components: {
    Header,
    HelloWorld,
    Form,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Rubik:wght@400;500;600;700&display=swap");
*,
*::before,
*::after {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  list-style: none;
  list-style-type: none;
  text-decoration: none;
}
body {
  font-family: "Rubik", ui-sans-serif, system-ui, -apple-system, sans-serif;
  font-weight: 400;
  line-height: 1.5;
}
</style>
