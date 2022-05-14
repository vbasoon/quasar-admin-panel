<template>
  <q-page padding>
    <h1>About</h1>
    <pre>{{ message }}</pre>
  </q-page>
</template>

<script>
import {ref} from 'vue'
export default {
  setup() {
    const message = 'Hello World!';
    return {
      message
    },
  }
}
</script>
