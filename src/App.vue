<template>
  <div id="app">
    <my-component />
  </div>
</template>

<script>
// import MyComponent from './components/MyComponent'
import MyComponent from "./components/MyComponent.vue";
export default {
  name: "App",
  components: {
    MyComponent,
  },
};
</script>