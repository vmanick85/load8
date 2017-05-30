<template>
    <div class="col-sm-4 col-sm-offset-4">
      <h2>Log In</h2>
      <p>Log in to your account to get some great quotes.</p>
       <div class="alert alert-danger" v-if="error">
         <p>{{ error }}</p>
      </div>
      <div class="form-group">
        <input
          type="text"
          class="form-control"
          placeholder="Enter your username"
        >
      </div>
      <div class="form-group">
        <input
          type="password"
          class="form-control"
          placeholder="Enter your password">
      </div>
      <div class="form-group">
        <a href="" style="'padding-top:6px'">Forgot Password?</a>
      </div>
      <button class="btn btn-primary" @click="submit()">Login</button>
    </div>
  </template>

  <script>
  export default {
    name: 'login',
    data () {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    }
  }
  </script>
