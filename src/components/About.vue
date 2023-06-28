<template>
    

    <div class="about" id="about">
        <h2 class="heading">About</h2>
        <div class="box"></div>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Laborum dolores facilis dolorum blanditiis qui veritatis consequatur! Reiciendis repellat unde impedit totam, laborum quam nesciunt, sint iste fuga neque omnis magnam.</p>
        
        <div class="about-contents">
            <div class="about-img">
                <img src="../assets/img/profile-img.jpg" class="about-imgs" alt="">
            </div>
            <div class="about-text">
                <h2 class="heading">UX/UI Developer & Web Developer</h2>
                <P>Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis facere ex</P>

                <div class="about-details">
                    <div class="about-details-col">
                        <p> <i class="fa fa-angle-right about-icon" aria-hidden="true"></i> <span class="bold">Age: </span>10</p>
                        <p>  <i class="fa fa-angle-right about-icon" aria-hidden="true"></i> <span class="bold">Website:</span> www.google.com</p>
                        <p> <i class="fa fa-angle-right about-icon" aria-hidden="true"></i> <span class="bold">Age: </span>10</p>
                       

                    </div>
                    <div class="about-details-col">
                        <p> <i class="fa fa-angle-right about-icon" aria-hidden="true"></i> <span class="bold">Age: </span> 10</p>
                        <p>  <i class="fa fa-angle-right about-icon" aria-hidden="true"></i> <span class="bold">Website: </span> www.google.com</p>
                        <p> <i class="fa fa-angle-right about-icon" aria-hidden="true"></i> <span class="bold">Age: </span>10</p>
     
                    </div>
                  
                  
                </div>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Expedita nemo voluptas hic modi, dolore vero nam neque possimus beatae fuga voluptatum autem ipsa velit a! Dicta inventore possimus molestiae veniam?</p>
            </div>
        </div>
    </div>




</template>

<script>

export default {
    name: "About",

}

</script>

<style>


    /* about */

  .about{
    padding: 5rem 10rem;
    margin-left: 250px;
   }
   .about-imgs{
     width: 300px;
     height: 300px;
   }

   .about-contents{
     display: flex;
     align-items: center;
     justify-content: center;
   }
   .about-text{
     padding-left: 5rem;
   }

   .about h1{
     margin: 0;
     padding: 0;
   }

   .about-details{
     display: grid;
     grid-template-columns: 1fr 1fr;

   }

   .about-icon{
    color: rgb(64, 160, 224);
   }


    

</style>
