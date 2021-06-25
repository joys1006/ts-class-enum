<script lang="ts">
import Vue from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { TsClassEnumSample } from '@/entry.esm';

export default Vue.extend({
  name: 'ServeDev',
  // components: {
  //  TsClassEnumSample,
  // }
});
</script>

<template>
  <div id="app">
    <ts-class-enum-sample />
  </div>
</template>
