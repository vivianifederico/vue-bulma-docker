<template>
  <div >
    <p>Original message: "{{ message }}"</p>
    <p class="is-danger">Computed reversed message: "{{ reversedMessage }}"</p>
  </div>
</template>

<script>
import Vue from 'vue'

export default Vue.extend({
  name: 'app',
  data: function () {
    return {message: 'Hello'}
  },
  computed: {
    reversedMessage: function () {
      return this.message.split('').reverse().join('')
    }
  }
})
</script>
