<script setup>
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "@/components/HelloWorld.vue";
</script>

<template>
  <header>
    <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>


  <div class="container-fluid">
        <!-- box header -->
        <header class="box-header">
            <div class="box-logo">
                <a href="index.html"><img src="@/assets/img/logo.png" width="200" alt="Logo"></a>
            </div>
            <!-- box-nav -->
            <a class="box-primary-nav-trigger" href="#0">
                <span class="box-menu-text">Menu</span><span class="box-menu-icon"></span>
            </a>
            <!-- box-primary-nav-trigger -->
        </header>
        <!-- end box header -->

        <!-- nav -->
        <nav>
            <ul class="box-primary-nav">
                <li class="box-label">MENU</li>

                <li><RouterLink to="/">Home</RouterLink> <i class="fa-solid fa-circle color"></i></li>
                <li><RouterLink to="/about">About me</RouterLink></li>
                <li><RouterLink to="/skills">Services & Skills</RouterLink></li>
                <li><RouterLink to="/portfolio">Portfolio</RouterLink></li>
                <li><RouterLink to="/contact">Contact me</RouterLink></li>



                <li class="box-label">Follow me</li>
                <li class="box-social"><a target="_blank" href="https://github.com/angelmavare"><i class="fa-brands fa-github"></i></a></li>
                <li class="box-social"><a target="_blank" href="https://www.linkedin.com/in/angel-mavare-801b12104/"><i class="fa-brands fa-linkedin-in"></i></a></li>
                <li class="box-social"><a target="_blank" href="https://twitter.com/angelmavare1"><i class="fa-brands fa-twitter"></i></a></li>
                <li class="box-social"><a target="_blank" href="https://www.instagram.com/angelmavare/"><i class="fa-brands fa-instagram"></i></a></li>

            </ul>
        </nav>
        <!-- end nav -->

       
    </div>

  <RouterView />
</template>

<style>
@import "@/assets/base.css";
@import "@/assets/css/all.min.css";
@import "@/assets/css/bootstrap.min.css";
@import "@/assets/css/style.css";

</style>
