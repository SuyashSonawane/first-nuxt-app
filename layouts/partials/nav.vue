<template>
    <header>
        <nuxt-link to="/" class="logo">NuxtApp</nuxt-link>
        <nav>
            <ul>
                <li><nuxt-link to="/" >Home</nuxt-link></li>
                <li><nuxt-link to="about" >About</nuxt-link></li>
                <li><nuxt-link to="services">Services</nuxt-link></li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {

}
</script>

<style scoped>

    header{
      
        background: rgb(77, 77, 77);
        display: grid;
        grid-template-columns: repeat(2,auto)
    }
    .logo{
        align-self: center
    }
   .logo ,li, a{
       padding: 0.5em 1.2em;
       display: block;
       text-decoration: none;
       text-transform: uppercase;
       font-weight: bold;
       color: white;
       font-size: 1.5em
   }
   nav{
       justify-self: right;

   }
   ul{

       list-style-type: none;
       display: inline-flex

   }
   li a {
       padding: 1em 2em;
       font-size: 0.45em;
       display: inline-block;
       background: rgba(0,0,0,0.1)
   }
</style>
