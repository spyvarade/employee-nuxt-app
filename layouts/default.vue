<template>
  <!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="">
    <meta name="author" content="Mark Otto, Jacob Thornton, and Bootstrap contributors">
    <meta name="generator" content="Jekyll v4.0.1">
    <title>Employee Management Application</title>  
  </head>

  <body>
     <div class="d-flex flex-column flex-md-row align-items-center p-3 px-md-4 mb-3 bg-white border-bottom shadow-sm">
        <h5 class="my-0 mr-md-auto font-weight-normal">Employee App</h5>
        <nav class="my-2 my-md-0 mr-md-3">
          <nuxt-link class="p-2 text-dark" to="/login">Login</nuxt-link>
          <nuxt-link class="p-2 text-dark" to="/register">Register</nuxt-link>
          <nuxt-link class="p-2 text-dark" to="/employee-list">Account</nuxt-link>
          <nuxt-link class="p-2 text-dark" to="#">Logout</nuxt-link>
        </nav>

      </div>
 <Nuxt />

</body>
</html>
  
</template>

<style>
 
</style>
