<template>
  <main role="main" class="container">
   
 
  <div class="starter-template">
    <h1>Manager Login</h1>
    <p class="lead">Login with manager account...</p>
    <form @submit="onSubmit" @reset="onReset" v-if="show">
      <div class="form-group">
        <label for="exampleInputEmail1">Email address</label>
        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" v-model="form.email">
        <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
      </div>
      <div class="form-group">
        <label for="exampleInputPassword1">Password</label>
        <input type="password" class="form-control" id="exampleInputPassword1" v-model="form.password">
      </div>
      
      <b-button type="submit" variant="primary">Submit</b-button>
      <b-button type="reset" variant="danger">Reset</b-button>
    </form>
  </div>

</main><!-- /.container -->
</template>

<script>
export default {
  data(){
    return{
      form:{
        email:'',
        password:'',
      },
      show:true
    }
  },

  methods:{
    onSubmit(evt){
      evt.preventDefault()
      alert(JSON.stringify(this.form))
      
    },
    onReset(){
      this.form.email = ''
      this.form.password = ''
    }
  }
}
</script>

<style scoped>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

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
