<template>
  <main role="main" class="container">
   
 
  <div class="starter-template">
    <div> 
      <h1>Employee List </h1> 
     
       <b-button v-b-modal.modal-1>Add Employee</b-button>
      <p class="lead">We Manage Our employee here...</p>
    </div>
    <hr>
      <form class="form-inline my-2 my-lg-0">
        <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
      </form>
    <table class="table table-hover">
      <thead>
        <tr>
          <th scope="col">#</th>
          <th scope="col">First Name</th>
          <th scope="col">Last Name</th>
          <th scope="col">Email</th>
          <th scope="col">Action</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th scope="row">1</th>
          <td>Mark</td>
          <td>Otto</td>
          <td>@mdo</td>
          <td>
            <a href="">View</a>
            <a href="">Edit</a>
            <a href="">Delete</a>

          </td>
        </tr>
        <tr>
          <th scope="row">2</th>
          <td>Jacob</td>
          <td>Thornton</td>
          <td>@fat</td>
          <td>@mdo</td>
        </tr>

      </tbody>
    </table>
    
   

     <b-modal id="modal-1" title="BootstrapVue">
       <p class="my-4">Hello from modal!</p>
     </b-modal>
  

  </div>

</main><!-- /.container -->
</template>

<script>
export default {
  data: () => ({
    showModal: true
  })
}
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
