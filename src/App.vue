<template>
  <div id="app">
    <SortableList />
  </div>
</template>

<script>
import SortableList from './components/SortableList.vue';

export default {
  name: 'App',
  components: {
    SortableList,
  },
};
</script>
