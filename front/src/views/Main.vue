<template>
  <div>
    <Navbar />
    <Sidebar />
    <MessageBoard />
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue';
import Sidebar from '@/components/Sidebar.vue';
import MessageBoard from '@/components/MessageBoard.vue';

export default {
  components: {
    Navbar,
    Sidebar,
    MessageBoard,
  },
  name: 'Main',
};
</script>

<style scoped>

</style>
