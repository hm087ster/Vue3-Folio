<template>

    <div class="container">
    <div class="inner">
        <div id="center">
      <div class="bloc">
        
      </div> 
      </div>
     
            <div class="bloc3">
               <p>Welcome to my website. This is where you'll 
               find all that I like to do...
               </p>  
               <p>
               And that is, to design things that are cool
               to look at on the web...
               </p>
            </div>
            <div class="line">..................................................................................................................................................................................................................................................................................................................</div>
            <div class="bloc2">My Skills</div>

        
          
            <div class="section">
                
            <span><img src="../assets/work.png" /></span>
            <span class="content">This is the place where I do all my coding... (HTML/ CSS/ JS and Vue3)
            </span>
            
            <span><img src="../assets/ques_mark.png" /></span>
            <span class="content2">In addition, I do the odd graphic too...(does
                that look like the Riddlers symbol?) 
            </span> 

            
            
           
            <span class="nodisplay"><img src="../assets/mug.png" /></span>
            <span class="content3">All made over a cup of tea... 
            </span> 
           

            </div>

            <div class="line">..................................................................................................................................................................................................................................................................................................................</div>
            <div class="bloc2">My Work</div>
            <div><video autoplay muted playsinline>
                <source src="../assets/footer.mp4" type="video/mp4">
            </video></div>
            <p class="content4">This is a flash banner done for a design agency, Hypergroup
            </p> 
            <div class="line">..................................................................................................................................................................................................................................................................................................................</div>
            <div class="bloc2">Contact Me</div>
            <p class="footer">If you like what I do, why not drop me an email or call me:
            </p>
            <p style="font-size:1.5rem;margin: 0 20px;text-align: left;">E: hm087ster@gmail.com</p>
            <p style="font-size:1.5rem;margin: 0 20px;text-align: left; padding-bottom: 10px;">Mob: +44 7377 644931</p>
        </div>
        </div>
</template>

<script>
    export default {
        name: 'Abo-ut',
        data (){
            return {}
        },
         
    }
    </script>
    <script setup>
   /* import { ref } from 'vue'
   const comp = ref()
   function scrollLeft(){
       comp.value.scrollIntoView({ behavior:'smooth' })
   }
   const comp2 = ref()
   function scrollMoreLeft(){
       comp2.value.scrollIntoView({ behavior:'smooth' })
   }*/
</script>

<style lang="scss" scoped>

@font-face{
		font-family: 'TT';
		src: url('../assets/TT Wellingtons Light.woff')format('woff');
		font-weight:100;
	}

*{
    box-sizing: border-box;
    font-family: 'TT';

}

.header{

    --font-size: 1.5rem
}

@media only screen 
and (max-device-width: 375px){


    .header{
    display:flex;
    align-items: center;
    justify-content: center;
    flex:1;
    height:60px;
    max-width: 100%;
    font-weight:500;
    color:#000;
    font-size: var(--font-size);
    }
    .inner{
    display:flex;
    flex-direction: column;
    row-gap: .5rem;
}
    .inner > div{
    flex: 1 1 auto;
    width:100%;
}

    #center{
        display:flex;
        justify-content: center;
        align-items: center;
        height: 70px
    }

    .bloc{
    background-image: url('../assets/logo_main.png');
    background-repeat: no-repeat;
    background-size:contain;
    height:35px;
    width:100px;
}

.bloc2{
    text-align: left;
    font-size:1.5rem;
    font-weight: 800;
    padding: 0 10px;
    color: #000;
    width: 100%;
}
.bloc3{
    text-align: left;
    font-size:1.5rem;
    padding:0px 20px;
    color: #000;
    word-wrap:break-word;
    width: 100%;
}

.section{
    display: flex;
    flex-direction: column;
    align-items: center;
}
.content{
    text-align: left;
    font-size: 1.5rem;  
    width: 100%;
    padding: 0 20px
}

.content2{
    text-align: left;
    font-size: 1.5rem;  
    width: 100%;
    padding: 0 20px;
}

.content3{
   display:none
}

.nodisplay{
    display:none
}
.content4{
    text-align: left;
    font-size: 1.5rem;  
    width: 100%;
    padding: 0 20px
}
.line
{
    font-size:1rem;
    line-height: 1.35rem;
    color: #111;
    width:100%;
    overflow-x:hidden;
}

.footer{
    text-align: left;
    font-size: 1.5rem;  
    width: 100%;
    padding: 0 20px
}

video{
    width: 100%;
    height: auto
}
}

@media only screen 
and (min-device-width: 376px)
and (max-device-width: 430px)
{

p{
    height:100%
}

.header{
    padding-left:10px;
    color:#000;
    display:flex;
    align-items: center;
    text-align: left;
    flex:1;
    height:70px;
    width: 100%;
    font-size: 1.75rem;
    font-weight:500;
}

.inner{
    display:flex;
    flex-direction: column;
    row-gap: 0.5rem;
}
.inner > div{
    flex: 1 1 auto;
    width:100%;
}

    #center{
        display:flex;
        align-items: center;
        justify-content: center;
        height: 70px;
    }
   .bloc{
    background-image: url('../assets/logo_main.png');
    background-repeat: no-repeat;
    background-size:contain;
    height: 35px;
    width:100px;
}

a{
    color:#000;
    text-decoration: none;
}

a:hover{
    cursor:pointer
}

.bloc2{
    text-align: left;
    padding: 0 10px;
    font-size:1.5rem;
    font-weight: 800;
    color: #000;
    max-width: 100%;
}
.bloc3{
    text-align: left;
    font-size:1.5rem;
    padding: 0 20px;
    line-height: 1.75rem;;
    color: #000;
    word-wrap:break-word;
    max-width: 100%;
}

.section{
    display: flex;
    flex-direction: column;
    align-items: center;
}
.content{
    text-align: left;
    font-size: 1.5rem;  
    width: 100%;
    padding: 0 20px
}
.section2{
    display: flex;
    flex-direction: column;
    align-items: center;
}
.content2{
    text-align: left;
    font-size: 1.5rem;  
    width: 100%;
    padding: 0 20px;
}
.section3{
    display:none
}
.content3{
   display:none
}
.nodisplay{
    display:none
}
.content4{
    text-align: left;
    font-size: 1.5rem;  
    width: 100%;
    padding: 0 20px
}

video{
    width: 90%;
    height: auto
}
.line
{
    font-size:1rem;
    line-height: 1.35rem;
    color: #111;
    width:100%;
    overflow-x:hidden;
}

.footer{
    text-align: left;
    font-size: 1.5rem;  
    width: 100%;
    padding: 0 20px
}

}

@media only screen 
and (min-width : 1224px) {


.container{
    width: 1000px;
    height:auto;
    margin: 0 auto;
}

.inner{
    display:flex;
    flex-direction: column;
    row-gap: .5rem;
}
    .inner > div{
    flex: 1 1 auto;
    width:100%;
}

#center{
        display:flex;
        justify-content: center;
        align-items: center;
        height: 70px
    }

    .bloc{
    background-image: url('../assets/logo_main.png');
    background-repeat: no-repeat;
    background-size:contain;
    height:35px;
    width:100px;
}

.bloc2{
    text-align: left;
    font-size:1.5rem;
    font-weight: 800;
    padding: 0 10px;
    color: #000;
    width: 100%;
}
.bloc3{
    text-align: left;
    font-size:3rem;
    padding:0px 20px;
    color: #000;
    word-wrap:break-word;
    width: 100%;
}

img{
    max-width:100%;
    height: auto;
}
.content{
    text-align: left;
    font-size: 1.25rem;  
    width:200px;
    margin: 0 0 0 30px;
}
.section{
    display: flex;
    justify-content:space-between;
    align-items:center;
    width: 40px;
}

.content2{
    text-align: left;
    font-size: 1.25rem;  
    width: 200px;
}

    .content3{
    text-align: left;
    font-size: 1.25rem;  
    width: 200px;
}
.content4{
    text-align: center;
    font-size: 1.25rem;  
    width: 100%;
    padding: 0 20px
}

.footer{
    text-align: left;
    font-size: 1.25rem;  
    width: 100%;
    padding: 0 20px
}

    video{
    width: 75%;
    height: auto
}

}
</style>