<template>
    <div class="register">
      <h1>Register</h1>
      <form @submit.prevent="register">
        <input v-model="nisn" type="text" placeholder="Masukkan NISN" required />
        <input v-model="nama" type="text" placeholder="Nama" required />
        <input v-model="password" type="password" placeholder="Password" required />
        <input v-model="confirmPassword" type="password" placeholder="Konfirmasi Password" required />
        <button type="submit">Daftar</button>
      </form>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        nisn: '',
        nama: '',
        password: '',
        confirmPassword: ''
      }
    },
    methods: {
      register() {
        // Registration logic here
      }
    }
  }
  </script>
  
  <style scoped>
  .register {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
    background-color: #f0f4f8;
    padding: 20px;
  }
  
  form {
    display: flex;
    flex-direction: column;
    width: 300px;
    background: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }
  
  input {
    margin-bottom: 15px;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
  }
  
  button {
    padding: 10px;
    background-color: #007bff;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
  }
  
  button:hover {
    background-color: #0056b3;
  }
  </style>
  