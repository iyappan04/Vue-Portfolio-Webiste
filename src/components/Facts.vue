<template>
    <div class="facts" id="facts">
        <h2 class="heading">Facts</h2>
        <div class="box"></div>
        <p>Magnam dolores commodi suscipit. Necessitatibus eius consequatur ex aliquid fuga eum quidem. Sit sint consectetur velit. Quisquam quos quisquam cupiditate. Et nemo qui impedit suscipit alias ea. Quia fugiat sit in iste officiis commodi quidem hic quas.</p>

        
        <div class="facts-row">
            <div class="facts-col">
                <div class="fact-emoji">
                    <p class="emojis"><i class="fa fa-envelope emoji emoji-color" aria-hidden="true"></i></p>
                </div>
               <div class="fact-text">
                    <h1>232</h1>
                    <p>Lorem ipsum dolor sit, amet consectetur.</p>
               </div>
            </div>
            <div class="facts-col">
                <div class="fact-emoji">
                    <p class="emojis"><i class="fa fa-envelope emoji emoji-color" aria-hidden="true"></i></p>
                </div>
               <div class="fact-text">
                    <h1>232</h1>
                    <p>Lorem ipsum dolor sit, amet consectetur.</p>
               </div>
            </div>
            <div class="facts-col">
                <div class="fact-emoji">
                    <p class="emojis"><i class="fa fa-envelope emoji emoji-color" aria-hidden="true"></i></p>
                </div>
               <div class="fact-text">
                    <h1>232</h1>
                    <p>Lorem ipsum dolor sit, amet consectetur.</p>
               </div>
            </div>
        </div>
    </div>

</template>


<script>

export default {
    name: "Facts",
}

</script>


<style>
       /* facts */

   .facts{
    padding: 5rem 10rem;
    margin-left: 250px;
   }
   .emojis{
      font-size: 3rem;
      color: rgb(55, 160, 221);
      margin: 0;
      padding: 0;
   }
   .emoji{
    border: 2px solid rgb(55, 160, 221);
    border-radius: 5rem;
    padding: 1rem;
   }
   .fact-text{
    padding-top: 2rem;
    padding-left: 2rem;
   }
   .facts-row{
     display: grid;
     grid-template-columns: 1fr 1fr 1fr;
     padding: 1rem 2rem;
     column-gap: 50px;
   }
   .emoji-color{
    color: #149ddd;
   }
   .facts h1{
      margin: 0;
      padding: 0;

   }
   .facts-col{
    display: flex;
    align-items: center;
    justify-content: center;
   }

   
</style>