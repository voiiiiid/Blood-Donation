<script>
  import { Router, Link, Route } from "svelte-routing";
  import Header from "./Header.svelte";
  import Hero from "./Hero.svelte";
  import Login from "./Login.svelte";
  import Register from "./Register.svelte";
  import About_Blood from "./About_Blood.svelte";
  import Donation_types from "./Donation_types.svelte";
  import Footer from "./Footer.svelte";
  export let url = "";
</script>

<Router {url}>
  <Header/>
  

  <div>
    <Route path="/login" component={Login} />
    <Route path="/register" component={Register} />
    <Route path="/about_blood" component={About_Blood} />
    <Route path="/about_blood/donations" component={Donation_types} />
    <Route path="/"><Hero /></Route>

  </div>

  <Footer/>
</Router>