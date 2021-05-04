<template>
    <div class="MenuCdp flex flex-directino-column">

        <div class="TextFoodTop flex flex-directino-column">
          <h2 class="TextDishing">Lorem Ipsum Dolor</h2>
          <p class="TextTop">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Distinctio rem, itaque officiis porro sapiente facilis.</p>
        </div>

      <div class="DishinCards flex "> 

          <div class="CardDish">
              <div class="ImgDishOne"></div>
              <h3>Lorem Ipsum</h3>
              <p>Lorem ipsum dolor sit amet, consectetur  adipisicing...</p>
          </div>

          <div class="CardDish">
              <div class="ImgDishTwo"></div>
              <h3>Lorem Ipsum</h3>
              <p>Lorem ipsum dolor sit amet, consectetur  adipisicing...</p>
          </div>

          <div class="CardDish">
              <div class="ImgDishThree"></div>
              <h3>Lorem Ipsum</h3>
              <p>Lorem ipsum dolor sit amet, consectetur  adipisicing...</p>
          </div>
      </div>

        <div class="ButtonHero flex">
         <span class="flex"><a class="More" href="">show more</a></span>
        </div>
    </div>
</template>

<script>
export default {
  name: 'SectionMenu'
}
</script>

<style scoped>

  .MenuCdp{
    height: 100vh;
    padding: 2%;
    box-sizing: border-box;
    justify-content: space-around;

  }
  .TextFoodTop {
    justify-content: center;
    align-items: center;
  }
  .TextDishing{
    text-align: center;
    font-family:'Reey';
    font-size: 3rem;
    font-weight: 300;
  }
  .TextTop{
    width: 33%;
    text-align: center;
    font-size: 1rem;
    margin: 0;
  }


  .DishinCards{
    justify-content: center;
    justify-content: space-evenly;
    margin: 2% 0 0 0;
  }
  .ImgDishOne{
    background-image: url('../assets/DishFoodOne.png');
    background-repeat: no-repeat;
    width: 15rem;
    height: 15rem;
  }
  .ImgDishTwo{
    background-image: url('../assets/DishFoodTwo.png');
    background-repeat: no-repeat;
    width: 15rem;
    height: 15rem;
  }
  .ImgDishThree{
    background-image: url('../assets/DishFoodThree.png');
    background-repeat: no-repeat;
    width: 15rem;
    height: 15rem;    
  }
  .CardDish{
    width: 19%;
    height: 15%;
  }
  .ButtonHero{
    justify-content: center;
  }

  span{
    width: 12rem;
    height: 2.5rem;
    background: #343434;
    border-radius: 20px;
    justify-content: center;
    align-items: center;
    margin: 1%;
  }
  .More{
    color: white;
    text-transform: uppercase;
    font-weight: 600;
  }

</style>