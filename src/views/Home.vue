<template>
  <div class="home">
    <FrontPage/>
  </div>
</template>

<script>
// @ is an alias to /src
import FrontPage from "@/components/FrontPage.vue";

export default {
  name: "Home",
  components: {
    FrontPage
  }
};
</script>
