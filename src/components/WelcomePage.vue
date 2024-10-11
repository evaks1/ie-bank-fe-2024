<template>
    <div class="jumbotron text-center">
      <h1>Welcome to IE Bank</h1>
      <p>Your trusted partner in banking solutions.</p>
      <router-link to="/accounts">
        <button class="btn btn-primary">Go to Accounts</button>
      </router-link>
    </div>
  </template>
  
  <script>
  export default {
    name: "WelcomePage",
  };
  </script>
  
  <style scoped>
  .jumbotron {
    margin-top: 50px;
    background-color: #0054a8;
    padding: 30px;
    border-radius: 10px;
  }
  h1 {
    font-size: 3rem;
  }
  p {
    font-size: 1.25rem;
  }
  </style>