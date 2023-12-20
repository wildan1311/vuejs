<template>
  <div class="container mt-5">
    <h1>{{ title }}</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Illum recusandae sed debitis
      iure in minus possimus aliquam nesciunt ipsam dolor, quia suscipit dolorum ea
      assumenda laudantium natus quos maxime doloremque.</p>
    <font-awesome-icon icon="shopping-cart"></font-awesome-icon>
    <Price :value="100"></Price>
  </div>
</template>

<script>
import { FontAwesomeIcon } from "@fortawesome/vue-fontawesome";
import Price from "./components/Price.vue";

export default {
  name: "App",
  data: function () {
    return {
      title: "IDSHOP"
    }
  },
  components: {
    FontAwesomeIcon,
    Price,
  },
};
</script>
