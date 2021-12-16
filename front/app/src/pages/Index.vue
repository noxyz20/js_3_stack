<template>
  <q-page class="flex flex-center bg-secondary">

    <q-uploader
        url="http://localhost:5000/upload"
        color="primary"
        flat
        @upload="postUpload"
        bordered
        style="max-width: 300px"
      />

  </q-page>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'PageIndex',
  methods: {
    postUpload (event) {
      console.log(event) // event is just the file name! The full response would be more useful
    }
  }
})
</script>
