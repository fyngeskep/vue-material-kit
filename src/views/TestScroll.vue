<script setup>
import TheWelcome from "../components/TheWelcome.vue";

let arr = [1,2,3,4,5,6,7,8,9,10];

</script>

<template>
  <main>
    <div class="container text-center">
      <h4 class="text-center">Count</h4>
      <table class="table table-sm">
        <thead>
          <th></th>
          <th></th>
          <th></th>
        </thead>
      </table>
      <p v-for="a in arr">
        {{a}}
      </p>
    </div>
  </main>
</template>
