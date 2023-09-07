<template>
  <div class="header">
    <h1>This is just logo</h1>
    <nav class="navigation">
      <ul>
        <li><a href="">Home</a></li>
        <li><a href="">About</a></li>
        <li><a href="">Login</a></li>
        <li><a href="">Register</a></li>
      </ul>
    </nav>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "TestingView",
});
</script>

<style scoped lang="scss">
$redColor: red;
.howdy {
  color: $redColor;
}

.header {
  display: flex;
  justify-content: space-between;
  background-color: green;
  align-items: center;
}

.header h1 {
  margin-left: 1rem;
}

.navigation ul {
  display: flex;
}

.navigation ul li {
  list-style: none;
}

.navigation ul li a {
  text-decoration: none;
  margin-right: 2rem;
}
</style>
