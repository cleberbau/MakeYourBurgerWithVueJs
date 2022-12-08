<template>
  <div>
    <ul>
      <li>
        <router-link to="/">Home </router-link>
      </li>
      <li>
        <router-link to="/about">Sobre</router-link>
      </li>
    </ul>
    <router-view></router-view>
  </div>

  
  </template>

<script>
export default {
  name: "App"

}
</script>