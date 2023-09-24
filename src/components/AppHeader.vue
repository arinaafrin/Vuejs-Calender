<template>
    <nav
      class="w-full bg-gradient-to-r from-blue-800 to-blue-600 text-white px-4 py-5"
    >
      <router-link class="mr-2" to="/">Home</router-link>
      <router-link class="mr-2" to="/">About Us</router-link>
      <router-link class="" to="/">Contact</router-link>
      <router-link
        key=""
        class="mx-2 hidden md:inline-block"
        to=""
        ></router-link
      >
      <div class="float-right">
        <button class="mx-2" @click="logout">Logout</button>
        <button  class="mx-2">
            Login
        </button>
      </div>
    </nav>
  </template>
  
  <script>

  </script>
  
  <style></style>