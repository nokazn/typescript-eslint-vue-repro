<template>
  <div>
    <!-- actually "no-unused-vars" error is reported at line 4 -->
    <p>foo</p>
  </div>
</template>

<script lang="ts">
import Vue from 'vue';
// the error should be reported at line 11
import Button from './Button.vue';

export default Vue.extend({});
</script>
