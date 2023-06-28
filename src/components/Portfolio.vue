<template>
     <div class="portfolio" id="portfolio">
        <h2 class="heading">Portfolio</h2>
        <div class="box"></div>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eveniet maxime, reprehenderit, nulla nobis dolor ratione cum saepe quidem qui, dolorum voluptatibus praesentium sit provident vitae rerum eum atque tempora suscipit.</p>
        <div class="portfolio-items-div">
            <div class="portfolio-items">
                <p>ALL</p>
                <p>APP</p>
                <p>CARD</p>
                <p>WEB</p>
            </div>
        </div>
       
        <div class="portfolio-images">
            <div class="portfolio-images-row">
                <div class="portfolio-img">
                    <img src="../assets/img/portfolio/portfolio-1.jpg" class="portfolio-image" alt="">
                </div>
                <div class="portfolio-img">
                    <img src="../assets/img/portfolio/portfolio-2.jpg" class="portfolio-image" alt="">
                </div>
                <div class="portfolio-img">
                    <img src="../assets/img/portfolio/portfolio-3.jpg" class="portfolio-image" alt="">
                </div>
            </div>
            <div class="portfolio-images-row">
                <div class="portfolio-img">
                    <img src="../assets/img/portfolio/portfolio-4.jpg" class="portfolio-image" alt="">
                </div>
                <div class="portfolio-img">
                    <img src="../assets/img/portfolio/portfolio-5.jpg" class="portfolio-image" alt="">
                </div>
                <div class="portfolio-img">
                    <img src="../assets/img/portfolio/portfolio-6.jpg" class="portfolio-image" alt="">
                </div>
            </div>
            <div class="portfolio-images-row">
                <div class="portfolio-img">
                    <img src="../assets/img/portfolio/portfolio-7.jpg" class="portfolio-image" alt="">
                </div>
                <div class="portfolio-img">
                    <img src="../assets/img/portfolio/portfolio-8.jpg" class="portfolio-image" alt="">
                </div>
                <div class="portfolio-img">
                    <img src="../assets/img/portfolio/portfolio-9.jpg" class="portfolio-image" alt="">
                </div>
            </div>
        </div>
    </div>

</template>


<script>

export default {
    name: "Portfolio",
}

</script>


<style>

    /* Portfolio Items */
   .portfolio{
      padding: 5rem 10rem;
      margin-left: 250px;
      background: #f5f8fd;
    }

    .portfolio-items-div{
      display: flex;
      align-items: center;
      justify-content: center;
      margin: 0;
      padding: 0;
    }

    .portfolio-items{
      border-radius: 2rem;
      background-color: rgb(235, 240, 240);
      display: flex;
      text-align: center;
   

    }
    .portfolio-items p{
      padding: 10px 20px;
      margin: 0;
      font-size: 12px;
    }
    .portfolio-images-row{
      display: flex;
      padding: 1rem 0;
      align-items: center;
      justify-content: center;
    }
    .portfolio-image{
      width: 400px;
      height: 300px;
    }
    .portfolio-img{
      padding: 1rem;
    }


</style>