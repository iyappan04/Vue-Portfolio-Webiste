<template>
      <div class="services" id="services">
        <h2 class="heading">Services</h2>
        <div class="box"></div>
        <p>Magnam dolores commodi suscipit. Necessitatibus eius consequatur ex aliquid fuga eum quidem. Sit sint consectetur velit. Quisquam quos quisquam cupiditate. Et nemo qui impedit suscipit alias ea. Quia fugiat sit in iste officiis commodi quidem hic quas.</p>


        <div class="services-rowes">
            <div class="services-rows">
                <div class="services-col">
                    <div class="services-icon-img">
                        <p class="service-icon"><i class="fa fa-envelope services-icon" aria-hidden="true"></i></p>
                    </div>
                    <div class="services-icon-contents">
                        <h4>Lorem Peasem</h4>
                        <p>Voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident</p>
                    </div>
                </div>
                <div class="services-col">
                    <div class="services-icon-img">
                        <p class="service-icon"><i class="fa fa-address-book services-icon" aria-hidden="true"></i></p>
                    </div>
                    <div class="services-icon-contents">
                        <h4>Lorem Peasem</h4>
                        <p>Voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident</p>
                    </div>
                </div>
                <div class="services-col">
                    <div class="services-icon-img">
                        <p class="service-icon"><i class="fa fa-book services-icon" aria-hidden="true"></i></p>
                    </div>
                    <div class="services-icon-contents">
                        <h4>Lorem Peasem</h4>
                        <p>Voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident</p>
                    </div>
                </div>
            </div>
            <div class="services-rows">
                <div class="services-col">
                    <div class="services-icon-img">
                        <p class="service-icon"> <i class="fa fa-credit-card services-icon" aria-hidden="true"></i> </p>
                    </div>
                    <div class="services-icon-contents">
                        <h4>Lorem Peasem</h4>
                        <p>Voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident</p>
                    </div>
                </div>
                <div class="services-col">
                    <div class="services-icon-img">
                        <p class="service-icon"><i class="fa fa-calendar services-icon" aria-hidden="true"></i></p>
                    </div>
                    <div class="services-icon-contents">
                        <h4>Lorem Peasem</h4>
                        <p>Voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident</p>
                    </div>
                </div>
                <div class="services-col">
                    <div class="services-icon-img">
                        <p class="service-icon">
                            <i class="fa fa-cloud services-icon" aria-hidden="true"></i>
                        </p>
                    </div>
                    <div class="services-icon-contents">
                        <h4>Lorem Peasem</h4>
                        <p>Voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident</p>
                    </div>
                </div>
            </div>
        </div>
      

    </div>
</template>

<script>

    export default {
        name: "Services",
    }

</script>


<style>
    
    /* Services */

    .services{
      padding: 5rem 10rem;
      margin-left: 250px;
    }

    .service-icon{
      font-size: 3rem;
      color: rgb(55, 160, 221);
      margin: 0;
      padding: 0;
      
    }
    .services-icon{
      border: 2px solid rgb(55, 160, 221);
      border-radius: 5rem;
      padding: 1rem;
    }
    .services-rows{
      display: flex;
    }
    .services-col{
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 1rem ;
    }
    .services-icon-contents p{
      font-size: 13px;
    }
    .services-icon-contents{
      padding-left: 2rem;
    }

</style>