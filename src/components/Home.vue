<template>
    <div class="background" id="home">
        <div class="content">
        <h1>Alex Smith</h1>
        <p class="bold text-animate">I am Freelancer</p>
        <div class="nav-toggle"><i class="fa fa-bars" aria-hidden="true"></i></div>
        </div>
    </div>
</template>

<script>

export default {
    name: "Home",
}

</script>

<style>



   
      /* home  */
    .background {
        background-image: url('../assets/img/hero-bg.jpg');
        background-size: cover;
        background-position: center;
        height: 100vh;
        display: flex;
        align-items: center;
        justify-content: center;
        margin-left: 200px; 
        padding: 0px 10px;
        background-attachment: fixed;
      }
    
       
      .content {
        color: white;
      }


      
    

  

</style>
