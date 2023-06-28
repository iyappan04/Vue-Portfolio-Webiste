<template>
    
    <div class="testmonials" id="testmonials">
        <h2 class="heading">Testmonials</h2>
        <div class="box"></div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus deleniti, temporibus blanditiis sit dolor illum perferendis fugit distinctio consequuntur animi nemo iste voluptas enim possimus aspernatur esse. Eos, ad doloremque.</p>

        <div class="testmonials-cards">
            <div class="testmoials-card">
                <p class="testmonials-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ducimus non vitae asperiores architecto et minus sed, alias eius officia harum nulla saepe consectetur error veniam, sunt, sit impedit sequi nihil.</p>
                <div class="testmonials-card-img">
                    <img src="../assets/img/testimonials/testimonials-1.jpg" class="testmonials-card-image" alt="">
                </div>
            </div>
            <div class="testmoials-card">
                <p class="testmonials-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ducimus non vitae asperiores architecto et minus sed, alias eius officia harum nulla saepe consectetur error veniam, sunt, sit impedit sequi nihil.</p>
                <div class="testmonials-card-img">
                    <img src="../assets/img/testimonials/testimonials-2.jpg" class="testmonials-card-image" alt="">
                </div>
            </div>
            <div class="testmoials-card">
                <p class="testmonials-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ducimus non vitae asperiores architecto et minus sed, alias eius officia harum nulla saepe consectetur error veniam, sunt, sit impedit sequi nihil.</p>
                <div class="testmonials-card-img">
                    <img src="../assets/img/testimonials/testimonials-3.jpg" class="testmonials-card-image" alt="">
                </div>
            </div>
        </div>
    </div>


</template>

<script>


export default {
    name: "Testmonials",
}

</script>

<style>
        /* testmonials */

    .testmonials{
      padding: 5rem 10rem;
      margin-left: 250px;
      background: #f5f8fd;
    }

    .testmonials-cards{
      display: flex;
      padding: 1rem 2rem;
      column-gap: 50px;
    }
    .testmoials-card{
      padding: 1rem;
      border-radius: .5rem;
      background: #f5f8fd;
      text-align: center;
     
    }

    .testmonials-text{
      padding: 2rem;
      box-shadow: 0 3px 10px rgb(230, 227, 227);

    }
  .testmonials-card-image{
    width: 100px;
    height: 100px;
    border-radius: 3rem;
  }

</style>


