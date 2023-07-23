
<template>
  <div>
    <h1>Data dari API GET:</h1>
    <ul v-if="responseData">
      <li v-for="post in responseData" :key="post.id">
        <h3>{{ post.title }}</h3>
        <p>{{ post.body }}</p>
      </li>
    </ul>
    <p v-else>Tidak ada data yang ditemukan.</p>
  </div>
</template>

<script>
import axios from 'axios';
const apiUrl = 'https://jsonplaceholder.typicode.com/posts';

export default {
  data() {
    return {
      responseData: null,
    };
  },
  mounted() {
    // Lakukan permintaan API GET saat komponen dimuat
    axios
      .get(apiUrl)
      .then(response => {
        this.responseData = response.data;
      })
      .catch(error => {
        console.error('Terjadi kesalahan:', error);
      });
  },
};

</script>