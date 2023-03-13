<script setup lang="ts">
import { VueElement } from 'vue';
import {ref} from 'vue';



</script>

<template>
  <div>
      <div>

    <ul id="nav"> 
      <li> <router-link to="/studio"> studio </router-link> </li>
      <li> <router-link to="/about"> about </router-link>  </li>
      <li> <router-link to="/booking"> booking </router-link> </li>
    </ul>

    </div>

    <div id="all"> 

      <div id="logo"> HEIM </div>
  

        <div id="content"> 

    
    
      <div id="info"> 
        <p>  wooden living space situated in downtown Bruvik. a small yet functional studio cabin, 
          designed with artists in mind.  </p>
        <button value="text"> BOOK NOW </button>
        </div>

     

      </div>

    </div>

    <About /> 
    </div>

</template>

<style> 
 @import "../src/css/base.css"; 
 
 


 #all {
  display: flex; 
  flex-direction: row;
 }

 #logo {
  writing-mode: vertical-rl;
  text-orientation: upright;
  margin-left: 4rem; 
  margin-top: 4%;
  letter-spacing: 4rem;
  font-size: 80px;
  animation: fadeIn 4s;
 }

 @keyframes fadeIn {
  from {

    opacity: 0%;
  }
  to {
    opacity: 100%;
  }
  
 }

 @keyframes infoFade {
  from {
    opacity: 0; 
  }
  to {
    opacity: 1; 
  }

 }


 footer {
  margin-bottom: 0rem; 
 }

 #nav {
  list-style-type: none;
  display: flex; 
  flex-direction: row;
  justify-content: space-around ;
  margin-left: 60%;
  font-size: 22px; 
  letter-spacing: 2px;

 }

 #cabin {
  height: 20%; 
  width: 10%; 
  margin-top: 10%; 
 }

 #content {
  display: inline-block;
  margin-top: 4%;
 }
 
 #info {
  margin-top: 16%;
  margin-left: 20%; 
  font-size: 32px;
  width: 40%; 
  animation: infoFade 6s; 
 
 }

 button{
  border: 2px solid black; 
  background-color: white;
  font-family: 'Times New Roman', Times, serif ;
  font-size: 18px; 

  width: 70; 
  height: 40px; 
 }

 #pic1 {
  margin-top: 40%;  
  width: 60%; 
  height: 60%; 
  rotate: 90deg; 
 }

 #page2{
  margin-top: 20%; 

 }

 #info2{

 }
</style>
