<template>

   
        <div class="sidenav">
            <img src="../assets/img/profile-img.jpg" class="profile" alt="">
            <h2>Alex Smith</h2>
            <p><i class="fa fa-instagram fab" aria-hidden="true"></i> <i class="fa fa-whatsapp fab" aria-hidden="true"></i> <i class="fa fa-linkedin fab" aria-hidden="true"></i> </p>
            <div class="sidenav-items">
                <a href="#home"> <i class="fa fa-home" aria-hidden="true"></i> Home</a>
                <a href="#about"> <i class="fa fa-user" aria-hidden="true"></i> About </a>
                <a href="#resume"> <i class="fa fa-file" aria-hidden="true"></i> Resumes </a>
                <a href="#portfolio"><i class="fa fa-file-image-o no-fa" aria-hidden="true"></i>Portfolio</a>
                <a href="#services"><i class="fa fa-server no-fa" aria-hidden="true"></i>Services</a>
            <a href="#contact"><i class="fa fa-envelope no-fa" aria-hidden="true"></i>Contact </a>
            </div>
            
        </div>

      

    
</template>

<script>

export default {
    name: "Sidebar",
}

</script>

<style>

     /* sidebar */


  .profile{
    width: 100px;
    height: 100px;
    border-radius: 5rem;
    border: 5px solid rgb(59, 59, 61);
  }


  .sidenav {
    padding: 2rem 2rem;
    height: 100%; 
    width: 250px; 
    position: fixed; 
    z-index: 1; 
    top: 0;
    left: 0;
    background-color: #111; 
    overflow-x: hidden; 
    padding-top: 20px;
    text-align: center;
    color: white;
    transition: transform 0.9s ease-out; /* Add a transition property */
  }

  .sidenav-items{
    padding-top: 2rem;
  }

  .sidenav a {
    padding: 1rem;
    text-decoration: none;
    color: white;
    display: block;
    text-align: left;
  }


  .sidenav a:hover {
    color: white;
  }

  .sidenav .fa:hover{
    color: rgb(64, 160, 224);
  }
  



   
 
</style>
