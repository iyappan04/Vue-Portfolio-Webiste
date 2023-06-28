<template>
  <div id="app">
    <Sidebar/>
    <Home/>
    <About/>
    <Facts/>
    <Skills/>
    <Resume/>
    <Portfolio/>
    <Services/>
    <Testmonials/>
    <Contact/>
    <UpArrow/>
    <Footer/>
  </div>
</template>

<script>


import Sidebar from './components/Sidebar.vue'
import Home from './components/Home.vue'
import About from './components/About.vue'
import Facts from './components/Facts.vue'

import Skills from './components/Skills.vue'
import Resume from './components/Resume.vue'
import Portfolio from './components/Portfolio.vue'
import Services from './components/Services.vue'
import Testmonials from './components/Testmonials.vue'
import Contact from "./components/Contact.vue"
import UpArrow from "./components/UpArrow.vue"
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    Sidebar,
    Home,
    About,
    Facts,
    Skills,
    Resume,
    Portfolio,
    Services,
    Testmonials,
    Contact,
    UpArrow,
    Footer,
  }
}
</script>

<style>



  body {
    margin: 0;
    padding: 0;
    font-family: "Open Sans", sans-serif;
    scroll-behavior: smooth;
  }
  *{
    scroll-behavior: smooth;
  }

  .bold{
    font-weight: bold;
  }

  h1 {
    font-size: 40px;
    margin-bottom: 20px;
  }
  
  .heading{
    color: #1f5297;
  }

  .show{
    display: block !important;
    transform: translateX(0) !important;
  }

  .hide{
    display: none;
  }


  .fa{
    padding: .5rem;
  }

  .fab{
    background-color: rgb(72, 73, 73);
    border-radius: 3rem;
    margin: .5rem;
  }

  .box{
    width: 50px;
    height: 5px;
    background-color: rgb(64, 160, 224);

    border-radius: 2rem;

  }

  .nav-toggle{
    display: none;
    position: fixed;
    right: 15px;
    top: 15px;
    z-index: 9998;
    border: 0;
    font-size: 24px;
    transition: all 0.4s;
    outline: none !important;
    background-color: rgb(64, 160, 224);
    color: #fff;
    width: 40px;
    height: 40px;
    align-items: center;
    justify-content: center;
    line-height: 0;
    border-radius: 50px;
    cursor: pointer;
  }

  .resume-box{
    padding: .5rem;
    font-size: 13px;
    font-weight: bold;
    background: #f5f8fd;
  }

  


   @media (max-width: 576px) {

    .sidenav {
      display: none;
    }

    
    .nav-toggle{
      display: inline-flex;
    }

    .background{
      margin: 0;
    }
    .about{
      padding: 1rem 1rem;
      margin: 0;
     }
     .about-contents{
      flex-direction: column;
     }
     .about-details{
      grid-template-columns: 1fr;
    }
    .about-text{
      padding: 1rem;
    }
   
    .facts{
      padding: 1rem;
      margin: 0;
    }

    .facts-row{
      grid-template-columns: 1fr;
    }
    .skills{
      margin: 0;
      padding: 1rem;
    }
    .skills-row{
      grid-template-columns: 1fr;
    }

    .resume{
      margin: 0;
      padding: 1rem;
    }
    .resumes-row{
      grid-template-columns: 1fr;
    }

    .portfolio{
      padding: 1rem;
      margin: 0;
    }
    .portfolio-images-row{
      padding: 1rem;
      flex-direction: column;
    }

    .services{
      margin: 0;
      padding: 1rem;
    }
    .services-rows{
      flex-direction: column;
    }

    .testmonials{
      padding: 1rem;
      margin: 0;
    }
    .testmonials-cards{
      flex-direction: column;
    }
    .testmonials-card{
      padding: 0;
    }
    .portfolio-image{
      width: 300px;
      height: 200px;
    }
    .testmonials-cards{
      padding: 1rem;
    }
    .contact{
      margin: 0;
      padding: 1rem;
    }
    .contact-row{
      grid-template-columns: 1fr;
    }
    .footer{
      display: none;
    }
   
    input{
      width: 80%;
    }
    .textarea{
      width: 80%;
    }
    .contact-col{
      padding: 1rem;
    }

   }


   @media only screen and (min-width: 577px) and (max-width: 768px) {
    .sidenav{
      display: none;
    }
    .nav-toggle{
      display: inline-flex;
    }

    .background{
      margin: 0;
    }
    .about{
      padding: 1rem 5rem;
      margin: 0;
     }
     .about-contents{
      flex-direction: column;
     }
     .about-details{
      grid-template-columns: 1fr;
    }
    .about-text{
      padding: 1rem;
    }

    .facts{
      padding: 1rem 5rem;
      margin: 0;
    }

    .facts-row{
      grid-template-columns: 1fr;
    }
    .skills{
      margin: 0;
      padding: 1rem 5rem;
    }
    .skills-row{
      grid-template-columns: 1fr;
    }

    .resume{
      margin: 0;
      padding: 1rem 5rem;
    }
    .resumes-row{
      grid-template-columns: 1fr;
    }

    .portfolio{
      padding: 1rem 5rem;
      margin: 0;
    }
    .portfolio-images-row{
      padding: 1rem;
      flex-direction: column;
    }

    .services{
      margin: 0;
      padding: 1rem 5rem;
    }
    .services-rows{
      flex-direction: column;
    }

    .testmonials{
      padding: 1rem 5rem;
      margin: 0;
    }
    .testmonials-cards{
      flex-direction: column;
    }
    .testmonials-card{
      padding: 0;
    }
    .portfolio-image{
      width: 300px;
      height: 200px;
    }
    .testmonials-cards{
      padding: 1rem;
    }
    .contact{
      margin: 0;
      padding: 1rem 5rem;
    }
    .contact-row{
      grid-template-columns: 1fr;
    }
    .footer{
      display: none;
    }
   
    input{
      width: 80%;
    }
    .textarea{
      width: 80%;
    }
    .contact-col{
      padding: 1rem;
    }

    }



    @media only screen and (min-width: 769px) and (max-width: 1024px) {
      .sidenav {
        padding: 1rem;
        height: 100%; 
        width: 220px; 
      }
      .background {
        margin-left: 150px; 
        padding: 0px 10px;
      }
      .about{
        padding: 1rem 2.5rem;
      }
      .about-contents{
        flex-direction: column;
      }
      .facts{
        padding: 1rem 2.5rem;
      }
      .facts-row{
        grid-template-columns: 1fr;
      }
      .skills{
        padding: 1rem 2.5rem;
      }
      .resume{
        padding: 1rem 2.5rem;
      }
      .portfolio{
        padding: 1rem 2.5rem;
      }
      .portfolio-images-row{
        flex-direction: column;
      }
      .services{
        padding: 1rem 2.5rem;
      }
      .services-rows{
        flex-direction: column;
      }
      .testmonials{
        padding: 1rem 2.5rem;
      }
      .testmonials-cards{
        padding: 1rem 3rem;
        flex-direction: column;
      }
      .contact{
        padding: 1rem 2.5rem;
      }
      .contact-row{
        grid-template-columns: 1fr;
      }



    }


      @media only screen and (min-width: 1024px) and (max-width: 1440px) {
      .about{
        padding: 1rem 2.5rem;
      }
      .sidenav {
        padding: 1rem;
        height: 100%; 
        width: 220px; 
      }
      .portfolio-image{
        width: 200px;
        height: 150px;
      }

      .facts{
        padding: 2rem 2.5rem;
      }

      .skills{
        padding: 2rem 2.5rem;
      }

      .resume{
        padding: 2rem 2.5rem;
      }

      .portfolio{
        padding: 2rem 2.5rem;
      }

      .services{
        padding: 2rem 2.5rem;
      }
      .testmonials{
        padding: 2rem 2.5rem;
      }
      .contact{
        padding: 2rem 2.5rem;
      }

    }




</style>
