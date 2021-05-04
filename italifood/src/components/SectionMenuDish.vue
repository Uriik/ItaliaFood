<template>
    <div class="DishisMenu flex flex-directino-column">

        <div class="ConstHeroDish flex ">
                <div class="ImageDishOne"></div>
                    <div class="HeroDish flex flex-directino-column">
                    <h3 class="TitleTextHead">Discount up to 50% All Excursions</h3>
                    <p class="TextHeadDish">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aut ipsa sunt placeat, reprehenderit maxime quae facilis esse ullam eos, laboriosam sit. Eligendi quidem magnam voluptates magni delectus impedit? Dolor, ex.</p>
                    <div class="ButtonHeroBot flex">
                        <span class="flex"><a class="MoreLorem" href="">read more</a></span>
                    </div>
                </div>
        </div>

        <div class="ConstHeroDishBot flex ">
                <div class="ImageDishTwo"></div>
                    <div class="HeroDish flex flex-directino-column">
                    <h3 class="TitleTextHead">January's Promo: Buy 1 Get 1 Free!</h3>
                    <p class="TextHeadDish">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aut ipsa sunt placeat, reprehenderit maxime quae facilis esse ullam eos, laboriosam sit. Eligendi quidem magnam voluptates magni delectus impedit? Dolor, ex.</p>
                    <div class="ButtonHeroBot flex">
                        <span class="flex"><a class="MoreLorem" href="">read more</a></span>
                    </div>
                </div>
        </div>

    </div>
</template>

<script>
export default {
  name: 'SectionMenu'
}
</script>

<style scoped>


    .DishisMenu{
        box-sizing: border-box;
        padding: 2%;

    }
    .ConstHeroDish, .ConstHeroDishBot{
        justify-content: center;
        justify-content: space-evenly;
    }
    .ConstHeroDish{
        margin-bottom: 2%;
    }
    .HeroDish{
        justify-content: space-between;
    }
    .ConstHeroDishBot{
        flex-direction: row-reverse;
    }

    .ImageDishOne{
        background-image: url('../assets/DishMenuOne.png');
        background-repeat: no-repeat;
        height:370px ;
        width: 370px;
    }
    .ImageDishTwo{
        background-image: url('../assets/DishMenuTwo.png');
        background-repeat: no-repeat;
        height:370px ;
        width: 370px;        
    }

  span{
    width: 12rem;
    height: 2.5rem;
    background: #27292c;
    border-radius: 20px;
    justify-content: center;
    align-items: center;
    margin: 1%;
  }
  h3{
      margin: 0;
  }
  .MoreLorem{
    color: white;
    text-transform: uppercase;
    font-weight: 600;
  }

  .TitleTextHead{
      font-size: 2.5rem;
      width: 25rem;
  }
  .TextHeadDish{
       width: 25rem;
  }

  .TextImage{
      justify-content: space-around;
  }
</style>