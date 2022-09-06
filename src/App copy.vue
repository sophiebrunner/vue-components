<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Welcome to Your Vue.js App" />
  <MyFirstComponent :headline="headline" type="" />
  <MyFirstComponent :headline="headline" type="red" />
  <MyFirstComponent :headline="headline" type="blue" />
  <MyFirstComponent :headline="headline" type="purple" />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import MyFirstComponent from "./components/MyFirstComponent.vue";
export default {
  name: "App",
  data() {
    return {
      headline: "My Headline Hi World",
    };
  },
  components: {
    HelloWorld,
    MyFirstComponent,
  },
};
</script>
