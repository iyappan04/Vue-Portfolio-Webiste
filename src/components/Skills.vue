<template>
     <div class="skills" id="skills">

        <h2 class="heading">skills</h2>
        <div class="box"></div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Est, voluptatibus. Deserunt totam numquam non, voluptatum, laborum necessitatibus ullam voluptas repellat earum, accusamus expedita est. Veritatis totam laborum illo sapiente soluta!</p>

        <div class="skills-row">
            <div class="skills-rows">
                <div class="skills-col">
                    <div class="progress">
                        <span>HTML  <span class="val">100%</span> </span>
                        <div class="progress-bar">
                            <div class="progress-bar-active">
    
                            </div>
                        </div>
                    </div>
                </div>
                <div class="skills-col">
                    <div class="progress">
                        <span>CSS  <span class="val">40%</span> </span>
                        <div class="progress-bar">
                            <div class="progress-bar-active" style="width: 40%;">
    
                            </div>
                        </div>
                    </div>
                </div>
                <div class="skills-col">
                    <div class="progress">
                        <span>PYTHON  <span class="val">65%</span> </span>
                        <div class="progress-bar">
                            <div class="progress-bar-active" style="width: 65%;">
    
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="skills-rows">
                <div class="skills-col">
                    <div class="progress">
                        <span>SASS  <span class="val">90%</span> </span>
                        <div class="progress-bar">
                            <div class="progress-bar-active" style="width: 90%;">
    
                            </div>
                        </div>
                    </div>
                </div>
                <div class="skills-col">
                    <div class="progress">
                        <span>DJANGO  <span class="val">50%</span> </span>
                        <div class="progress-bar">
                            <div class="progress-bar-active" style="width: 50%;">
    
                            </div>
                        </div>
                    </div>
                </div>
                <div class="skills-col">
                    <div class="progress">
                        <span>LINUX <span class="val">75%</span> </span>
                        <div class="progress-bar">
                            <div class="progress-bar-active" style="width: 75%;">
    
                            </div>
                        </div>
                    </div>
                </div>
                
            </div>
        </div>
    </div>

</template>

<script>


export default {
    name: "Skills",

}

</script>

<style>

       /* skills */

   .skills{
    padding: 5rem 10rem;
    margin-left: 250px;
    background: #f5f8fd;
   }

   .progress{
     display: block;
   }
   .val{
     float: right;
   }
   .progress-bar{
    background: #dce8f8;
    height: 10px;
   }
   .progress-bar-active{
    height: 10px;
    transition: 0.9s;
    background-color: #149ddd;
   }
   .skills-row{
     display: grid;
     grid-template-columns: 1fr 1fr;
   }
   .skills-rows{
     padding: 1rem 1rem 1rem 0rem;
   }
   .skills-col{
     padding: 1rem 0rem;
   }

</style>
