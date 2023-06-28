<template>
    <div class="resume" id="resume" >
        <h2 class="heading">Resumes</h2>
        <div class="box"></div>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde eligendi nobis dignissimos quis consequuntur quas veritatis illo, libero distinctio mollitia cumque nulla commodi omnis? Ut nostrum accusamus sed. Voluptate, eos.</p>


        <div class="resume-row">
            <div class="resumes-row">
                <div class="resume-col">
                    <h3>Summary</h3>
                    <div class="resume-item">
                        <h3>ALEX SMITH</h3>
                        <P>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate repellendus quam, quidem </P>
                        <ul>
                            <li>India, Tamil Nadu</li>
                            <li>+91 4569694934</li>
                        </ul>
                    </div>
                </div>
                <div class="resume-col">
                    <h3>Professional Experience</h3>
                    <div class="resume-item">
                        <h3>ALEX SMITH</h3>
                        <span class="resume-box">2019 - Present</span>
                        <P>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate repellendus quam, quidem </P>
                        <ul>
                            <li>India, Tamil Nadu</li>
                            <li>+91 4569694934</li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="resumes-row">
                <div class="resume-col">
                    <h3>Summary</h3>
                    <div class="resume-item">
                        <h3>ALEX SMITH</h3>
                        <P>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate repellendus quam, quidem </P>
                        <ul>
                            <li>India, Tamil Nadu</li>
                            <li>+91 4569694934</li>
                        </ul>
                    </div>
                </div>
                <div class="resume-col">
                    <h3>Professional Experience</h3>
                    <div class="resume-item">
                        <h3>ALEX SMITH</h3>
                        <P>Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate repellendus quam, quidem </P>
                        <ul>
                            <li>India, Tamil Nadu</li>
                            <li>+91 4569694934</li>
                        </ul>
                    </div>
                </div>
            </div>
            
        </div>
    </div>
</template>

<script>

export default{
    name: "Resume",
}

</script>

<style>



   /* resume */

   .resume{
     padding: 5rem 10rem;
     margin-left: 250px;
   }
   .resumes-row{
     padding: 1rem;
     display: grid;
     grid-template-columns: 1fr 1fr;
   }
   .resume-item{
    padding: 0 0 20px 20px;
    margin-top: -2px;
    border-left: 2px solid #1f5297;
    position: relative;
   }
   .resume-item::before{
    content: "";
    position: absolute;
    width: 16px;
    height: 16px;
    border-radius: 50px;
    left: -10px;
    top: 0;
    background: #fff;
    border: 2px solid #1f5297;
   }

   .resume li{
     padding: .5rem 0;
   }



</style>
