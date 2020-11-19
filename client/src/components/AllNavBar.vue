<template>
    <div id="all-nav-bar">
    <nav class="navbar navbar-expand navbar-dark bg-dark">
      <router-link to="/" class="navbar-brand">PUWANAT</router-link>
      <div class="navbar-nav mr-auto">
        <li class="nav-item">
          <router-link to="/tutorials" class="nav-link">Tutorials</router-link>
        </li>
        <li class="nav-item">
          <router-link to="/add" class="nav-link">Add</router-link>
        </li>
      </div>
    </nav>
  </div>
</template>
<script>
export default {
    name:"all-nav-bar",
    data(){
        return{

        }
    }
}
</script>