<template>
  <div>
    <h1>Home</h1>
    <v-card>
      <v-card-text>
        <my-counter />
      </v-card-text>
    </v-card>
  </div>
</template>

<script lang="ts">
import Vue from 'vue';
import MyCounter from '@/components/my-counter.vue'; // @ is an alias to /src

export default Vue.extend({
  components: {
    MyCounter,
  },
});

</script>
