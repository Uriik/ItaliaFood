<template>
    <div class="HeroSect flex  flex-directino-column">

        <div class="TitlteLor flex">
            <h2>Lorem Ipsum Dolor</h2>
        </div>
        
        <div class="TextCenter flex">
            <div><p class="TextHeroLor">Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusamus eveniet molestiae saepe ullam assumenda minus dolores praesentium, explicabo eius nam ad similique, modi, commodi deleniti. Facere fugiat sed sequi nostrum?</p></div>
            <div><p class="TextHeroLor">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quos, reprehenderit veniam mollitia vitae assumenda illum accusantium fugiat eum voluptatibus voluptate, natus inventore! Cumque aliquam cum quod consequuntur ea voluptatum omnis?</p></div>
        </div>

        <div class="ButtonHeroBot flex">
            <span class="flex"><a class="MoreLorem" href="">show more</a></span>
        </div>
    </div>
</template>

<script>
export default {
  name: 'SectionMenu'
}
</script>

<style scoped>

    .HeroSect{
        background: #27292c;
        box-sizing: border-box;
        padding: 2%;
        justify-content: center;
    }
    h2{
        font-family: 'Reey';
        color: white;
        font-weight: 300;
        font-size: 3.0rem;
    }
    .TitlteLor{
        justify-content: center;
    }

    .TextHeroLor{
        width: 85%;
        height: auto;
        margin: 5% auto;
        color: white;
    }

    .ButtonHeroBot{
    justify-content: center;
  }

  span{
    width: 12rem;
    height: 2.5rem;
    background: white;
    border-radius: 20px;
    justify-content: center;
    align-items: center;
    margin: 1%;
  }
  .MoreLorem{
    color: #343434;
    text-transform: uppercase;
    font-weight: 600;
  }

</style>