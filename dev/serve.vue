<script>
import Vue from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
import { UIcard } from '@/entry.esm';
import { UIbutton } from '@/entry.esm';

export default Vue.extend({
  name: 'ServeDev',
  components: {
   UIcard,
   UIbutton,
  }
});
</script>

<template>
  <div id="app">
    <UIcard alignment="vertical"/>
    <UIbutton text="Click Me" classname="outlined"/>
  </div>
</template>
