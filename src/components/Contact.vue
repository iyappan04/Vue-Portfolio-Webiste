<template>
     <div class="contact" id="contact">
        <h2 class="heading">Contact</h2>
        <div class="box"></div>
        <p>Magnam dolores commodi suscipit. Necessitatibus eius consequatur ex aliquid fuga eum quidem. Sit sint consectetur velit. Quisquam quos quisquam cupiditate. Et nemo qui impedit suscipit alias ea. Quia fugiat sit in iste officiis commodi quidem hic quas.</p>
        <div class="contact-row">
            <div class="contact-col">
                <div class="contacts-row">
                    <div class="contacts-img">
                        <i class="fa fa-location-arrow contact-icon" aria-hidden="true"></i>
                    </div>
                    <div class="contacts-text">
                        <h3>  Location</h3>
                        <p>Chennai, TN, 620101</p>
                    </div>
                </div>
               
                <div class="contacts-row">
                    <div class="contacts-img">
                        <i class="fa fa-envelope contact-icon" aria-hidden="true"></i>
                    </div>
                    <div class="contacts-text">
                        <h3>  Email</h3>
                        <p>chadura@gmail.com</p>
                    </div>
                </div>

                <div class="contacts-row">
                    <div class="contacts-img">
                        <i class="fa fa-phone contact-icon" aria-hidden="true"></i>
                    </div>
                    <div class="contacts-text">
                        <h3>  Phone</h3>
                        <p>9369359249</p>
                    </div>
                </div>

                <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d12097.433213460943!2d-74.0062269!3d40.7101282!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xb89d1fe6bc499443!2sDowntown+Conference+Center!5e0!3m2!1smk!2sbg!4v1539943755621" frameborder="0"></iframe>
            </div>
            <div class="contact-col">
                <form class="form-control">
                    <p>Your Name</p>
                    <input type="text" name="name" placeholder="Username">
                    <!-- <p>Mail</p>
                    <input type="text" name="name" placeholder="Username"> -->
                    <p>Subject</p>
                    <input type="text" class="subject" placeholder="Message">
                    <p>Message</p>
                    <textarea name="message" id="" cols="50" rows="10" class="textarea"></textarea>
                    <br><br>
                    <button class="btn">Send Message</button>
                </form>
                
            </div>
        </div>
    </div>
</template>


<script>

export default {
    name: "Contact",
}


</script>

<style>

    /* Contact */

  .contact{
    padding: 5rem 10rem;
    margin-left: 250px;
  }

  .contact-row{
    padding: 2rem 0;
    display: grid;
    grid-template-columns: 1.5fr 2fr;
    column-gap: 50px;
    
  }

  .contact-icon{
    padding: 1rem;
    border-radius: 3rem;
    color: rgb(84, 168, 236);
    border: 1px solid rgb(84, 168, 236);
  }

  .contact-col{
    box-shadow: 0 3px 10px rgb(230, 227, 227);
    padding: 1rem 2rem;
    border-radius: 1rem;
  }

  .contacts-row{
    display: flex;
    align-items: center;
  }

  .contacts-text{
    padding-top: 1rem;
    padding-left: 1rem;
  }

  iframe{
    padding: 1rem 0;
    width: 100%;
    height: 30vh;
  }

  .contact input{
    padding: 1rem;
    outline: none;
    border: 1px solid rgb(55, 160, 221);
    border-radius: .5rem; 
  }

  .contact .fa:hover{
    color: white;
    background: rgb(55, 160, 221);

  }

 

  textarea{
    padding: 1rem;
    outline: none;
    border: 1px solid rgb(55, 160, 221);
    border-radius: .5rem; 
    min-height: 200px;

  }

  .form-control{
    display: block;
    padding: 1rem;
  }

   
  input{
    width: 80%;
  }
  .textarea{
    width: 80%;
  }
  .btn{
    padding: 1rem;
    border-radius: .5rem;
    background-color: rgb(55, 160, 221);
    color: white;
    border: none;
    outline: none;
  }


</style>