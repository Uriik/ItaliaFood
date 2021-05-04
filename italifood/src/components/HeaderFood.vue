<template>
  <div class="HeroFood flex flex-directino-column">

    <div class="GroupFoodHero">

        <div class="MenuHeroContent flex">
          
          <h1 class="ContLogo flex flex1">
             <a href=""><img src="../assets/LogoHeroHeader.png" alt=""></a>
          </h1>

          <nav class="ListMenuHero flex flex2">
              <ul class="MenuConst flex flex1">
                <li><a href="">HOME</a></li>
                <li><a href="">MENU</a></li>
                <li><a href="">OUR STORY</a></li>
                <li><a href="">CONTACT US</a></li>
              </ul>
          </nav>

          <div class="SearchHero flex flex1">
            <div class="search-box">
              <label for="eat"></label>
              <input class="search-txt " type="search" name="">
              <a class="search-btn" href="#"></a>
              <a href=""><i class="fas fa-search"></i></a>
            </div>
          </div>
      </div>

        <div class="TextFoodImg flex">
            <div  class="TextNameRest flex flex-directino-column">
              <h2 class="Reey">Italian Food</h2>
              <p class="TextSun">Loremipsum dolor</p>

              <div class="ReadHere flex flex-directino-column">
                <div class="flex">
                  <span class="ReadBut"><a href=""><p class="ReadHero">Read More</p></a></span>
                </div>
                <p class="TextHeroF">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque atque repellendus non iusto eum corrupti dolorem incidunt nostrum, ea labore perferendis commodi odio facere praesentium quisquam cum minima harum recusandae.</p>
              </div>
            </div>

            <div class="DishRest flex">
              <div class="Dish"></div>
            </div>
        </div>
        <div class="Leaves"></div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'HeaderFood'
}
</script>

<style scoped>
    .HeroFood{
      height: auto;
      box-sizing: border-box;
    }
    .GroupFoodHero{
      background-image:url('../assets/BackgroundHeaderFood.png') ;
      background-repeat:no-repeat ;
      background-size:cover ;
      height: 100vh;
      box-sizing: border-box;
      padding: 2% 2% 0 2%;
    }
    .ContLogo{
      justify-content: center;
    }

    .MenuHeroContent{
      height: 11%;
      /* border: solid 1px red; */
    }
    h1{
      margin: 0;
    }
    a{
      text-decoration: none;
    }
    ul{
      padding: 0;
      margin: 0;
      list-style: none;
    }
    .ListMenuHero{
      align-items: center;
      justify-content: center;
    }
    .MenuConst a{
      color: white;
      
    }
    .MenuConst, li{
      justify-content: space-evenly;
      align-items: center;
    }
    .SearchHero{
      justify-content: center;
      align-items: center;
    }
    .search-box{
      background: white;
      height: 20px;
      border-radius: 40px;
      padding: 10px;
    }
    .search-btn{
      color: #e84118;
      float: right;
      width: 20px;
      border-radius: 40%;
      background: #343434;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .search-txt{
      border: none;
      background: none;
      outline: none;
      float: left;
      padding: 0;
      color: black;
      font-size: 15px;
      transition: 0.4s;
      line-height: 20px;
      width: 190px;
    }
    .fa-search{
      color: #343434;
    }

    .TextFoodImg{
      height:89%;
      justify-content: space-between;
    }
    .TextNameRest{
      box-sizing: border-box;
      padding: 5%;
      height: 100%;
      width: 100%;
      justify-content: space-between;
    }
    .DishRest{
      height: 100%;
      width: 100%;
      justify-content: center;
    }
    .Dish{
      background-image: url('../assets/DishFood.png');
      background-repeat: no-repeat;
      height:450px ;
      width: 500px;
      align-self: center;
    }
    .Reey{
      padding: 0;
      margin: 0;
      font-family:'Reey';
      font-weight: normal;
      font-size: 5rem;
      color: white;
    }
    .TextSun{
      color: white;
      font-size: 1.0rem;
      text-transform: uppercase;
      font-weight: 400;
      font-style: italic;
    }
    .ReadHere{
      justify-content: space-between;
    }
    span, .Readbut{
      width: 30%;
      height: auto;
      text-align: center;
      border-radius: 10rem;
      text-transform: uppercase;
      background-color: white;
    }
    .ReadHero{
      color: #343434;
      font-weight: 600;
    }
    .TextHeroF{
      color: white;
    }
    .Leaves{
      background-image:url('../assets/LeavesHero.png') ;
      background-repeat: no-repeat;
      position: relative;
      bottom: 50%;
      height: 80%;
      width: 29%;
      z-index: 1000;
      margin: 0 0 0 auto;
    }


</style>
