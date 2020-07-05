<template>
  <main role="main" class="container">
   
 
  <div class="starter-template">
    <h1>Manager Register</h1>
    <p class="lead">We Manage Our employee here...</p>

    <form>
      <div class="row">
        <div class="form-group col-6">
          <label>Email address</label>
          <input type="email" class="form-control" >
        </div>
        <div class="form-group col-6">
          <label>First Name</label>
          <input type="email" class="form-control" >
        </div>
        <div class="form-group col-6">
          <label>Last Name</label>
          <input type="email" class="form-control" >
        </div>
        <div class="form-group col-6">
          <label for="exampleInputPassword1">Password</label>
          <input type="password" class="form-control" >
        </div>
        <div class="form-group col-12">
          <label> Address</label>
          <textarea  class="form-control" ></textarea>
        </div>
        <div class="form-group col-6">
          <label>DOB</label>
          <input type="date" class="form-control" >
        </div>
        <div class="form-group col-6">
          <label>Company</label>
          <input type="text" class="form-control" >
        </div>
      </div>
        
      <button type="submit" class="btn btn-primary">Register</button>
    </form>

  </div>

</main><!-- /.container -->
</template>

<script>
export default {}
</script>

<style>


.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
