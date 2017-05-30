<template>
<div id="wrapper">
  <nav class="navbar navbar-inverse">
    <div class="container-fluid">
      <div class="navbar-header">
        <a class="navbar-brand" href="#">
          <i class="glyphicon  glyphicon-refresh glyphicon-refresh-animate"></i>
            Load8
       </a>
      </div>
      <ul class="nav navbar-nav">
        <li><router-link to="/home">Home</router-link> </li>
        <li><router-link to="/dashboard">Dashboard</router-link></li>
      </ul>
     <ul class="nav navbar-nav navbar-right">
    <li><router-link to="/login">Login</router-link> </li>
    <li><router-link to="/register">Register</router-link></li>
    <li><router-link to="/login">Logout</router-link></li>
    </ul>
    </div>
  </nav>
  <div class="container">
      <router-view></router-view>
  </div>
</div>
</template>
