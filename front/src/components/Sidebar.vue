<template>
  <div>
<!--    <ul class="sidenav sidenav-fixed" style="transform: translateX(0%);">-->
<!--      <li class="search-wrapper">-->
<!--        <i class="material-icons">search</i>-->
<!--        <input type="text" placeholder="Search">-->
<!--      </li>-->
<!--      <li class="bold" v-for="contact in contacts" :key="contact.id">-->
<!--        <a href="#" class="waves-effect waves-teal">-->
<!--          {{ contact.name }}-->
<!--        </a>-->
<!--        <p>-->
<!--          {{ contact.lastMessage }}-->
<!--        </p>-->
<!--      </li>-->
<!--    </ul>-->
    <ul class="collection sidenav sidenav-fixed" style="transform: translateX(0%);">
      <li class="collection-item avatar" v-for="contact in contacts" :key="contact.id">
        <i class="material-icons circle green">insert_chart</i>
        <span class="title">{{ contact.name }}</span>
        <p>{{ contact.status}}<br>
          {{ contact.lastMessage }}
        </p>
        <a href="#!" class="secondary-content"><i class="material-icons">grade</i></a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Sidebar',
  data() {
    return {
      contacts: [
        {
          id: 1,
          name: 'Valeriy',
          status: 'online',
          lastMessage: 'how do you do',
        },
        {
          id: 2,
          name: 'Alexandra',
          status: 'online',
          lastMessage: 'no war',
        },
        {
          id: 3,
          name: 'goverment',
          status: 'offline',
          lastMessage: 'no result',
        },
      ],
    };
  },
};
</script>

<style scoped>

</style>
