<template>
    <div class="BackgroundPiz flex flex-directino-column">
        <div class="ContainerPiz flex flex-directino-column">

            <h2 class="TitleBackPiz">Lorem Ipsum Dolor Sit Amer</h2>
            <p class="TextBackPiz">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis </p>

            <div class="ImgPizza"></div>

            <div class="LeaveBotleft"></div>
            <div class="LeaverBotrigth"></div>
        </div>
        

    </div>
</template>

<script>
export default {
  name: 'SecArtPizz'
}
</script>
<style scoped>

    @media (min-width:1820px) and (max-width: 1980px){
        div .ImgPizza{
            position: absolute;
            top: 223rem;
            background-image:url('../assets/BackgroundPiz.png') ;
            background-repeat: no-repeat;
            height: 790px;
            width: 778px;
        }
        div .LeaveBotleft{
            position: absolute;
            right: 90rem;
            top: 205rem;
        }
            div .LeaverBotrigth{
            position: relative;
            left: 40rem;
            top: -20rem;          
        }
    }

    .BackgroundPiz{
        background-image: url('../assets/BackgroundHeaderFood.png');
        background-repeat: no-repeat;
        background-size:cover ;
        height: 100vh;
        padding: 2% 2% 0 2%;

    }
    .ContainerPiz {
        justify-content: center;
        align-items: center;  
            
    }
    .TitleBackPiz{

        font-family: 'Reey';
        font-weight: 300;
        font-size: 3.0rem;
        color: white;
        align-items: center;
        margin-bottom: 2rem;
    }
    .TextBackPiz   {
        font-size: 1.0rem;
        color: white;
        width: 50%;
        text-align: center;

    }
    .ImgPizza{
        background-image:url('../assets/BackgroundPizMini.png') ;
        background-repeat: no-repeat;
        position: absolute;
        top: 170rem;
        height: 573px;
        width: 582px;
        z-index: 1000;      
    }
    .LeaveBotleft{
        background-image: url('../assets/LeaverBotleft.png');
        background-repeat: no-repeat;
        height: 400px;
        width: 275px;
        z-index: 1000;
        position: absolute;
        right: 65rem;
        top: 160rem;
    }
    .LeaverBotrigth{
        background-image: url('../assets/LeaverBotrigth.png');
        background-repeat: no-repeat;
        height: 677px;
        width: 285px;
        z-index: 1000;
        position: relative;
        left: 30rem;
        top: -20rem;
        background-size:cover ;

    }

</style>