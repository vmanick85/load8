<template>
  <div class="col-sm-4 col-sm-offset-4">
    <h2>Register</h2>
    <p>Register for a free account</p>
    <div class="alert alert-danger" v-if="error">
      <p>{{ error }}</p>
    </div>
    <div class="form-group">
      <input
        type="text"
        class="form-control"
        placeholder="First Name">
    </div>
    <div class="form-group">
      <input
        type="text"
        class="form-control"
        placeholder="Last Name">
    </div>
    <div class="form-group">
      <input
        type="text"
        class="form-control"
        placeholder="Enter your username">
    </div>
    <div class="form-group">
      <input
        type="password"
        class="form-control"
        placeholder="Enter your password"
      >
    </div>
    <div class="form-group">
      <input
        type="password"
        class="form-control"
        placeholder="Confirm password"
      >
      </div>
    <button class="btn btn-primary" @click="submit()">Register</button>
  </div>
</template>

<script>

</script>
