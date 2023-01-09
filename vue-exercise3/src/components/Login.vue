<template>
    <div>
        <form @submit.prevent="login">
          <label for="name">Name:</label>
          <input class="name" type="name" placeholder="Name" v-model="name" required />
          <br />
          <label for="email">Email:</label>
          <input class="email" type="email" placeholder="Email" v-model="email" required />
          <br />
          <label for="password">Password:</label>
          <input class="password" type="password" placeholder="Password" v-model="password" required />
          <br />
          <button v-on:click="alertPurchase" type="submit">Login</button>
        </form>
      </div>
</template>
<script>
export default {
data() {
    return {
    name: "",
    email: "",
    password: ""
    };
},
methods: {
    login() {
    // Perform login logic here, such as making a request to a server to authenticate the user
    console.log("Log In Name: " + this.name + " and email: " + this.email + " and password: " + this.password);
    }
}
};
</script>
<style>
.name{
    margin-top: 2rem; 
    width: 50rem;
    height: 3rem
}
.email{
    margin-top: 2rem; 
    width: 50rem;
    height: 3rem
}
.password{
    margin-top: 2rem; 
    margin-right: 2rem;
    width: 50rem;
    height: 3rem
}
</style>