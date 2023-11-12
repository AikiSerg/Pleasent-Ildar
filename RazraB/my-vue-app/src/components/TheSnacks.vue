<template>
    <div class="Snacks">
        <div class="ShapkaSnacks">
            <p class="SnacksTitle">
                Закуски
            </p>
            <div class="logoSnacks_1">
                <img src="../assets/o_donut.png">
            </div>
            <div class="logoSnacks_2">
                <img src="../assets/Cup.png">
            </div>
        </div>
        <p class="SnacksText">
            Здесь есть несколько простых рецептов закусок, <br>
            которые ты можешь подготовить к просмотру
        </p> 
        <div class="SnacksUrls">
            <div class="SnackWrapper">
                <p class="SnackUrlsText">
                    Сендвич
                </p>
            </div>
            <div class="SnackWrapper">
                <p class="SnackUrlsText">
                    Сендвич
                </p>
            </div>
            <div class="SnackWrapper">
                <p class="SnackUrlsText">
                    Сендвич
                </p>
            </div>
            <div class="SnackWrapper">
                <p class="SnackUrlsText">
                    Сендвич
                </p>
            </div>
            <div class="SnackWrapperAbove">
                <img src="../assets/Icon.png">
            </div>
            <div class="SnackWrapperAbove">
                <img src="../assets/Icon2.png">
            </div>
                <div></div>
                <div></div>
            
        </div>      
    </div>
</template>

<script>
export default {
    name: 'TheSnacks',
    props: {
        msg: String
    }
}
</script>
    
<style>
  /* Вставьте ваш CSS код здесь */
.Snacks {
/*    width: 1440px; */
    height: 840px;
    border-radius: 85px;
    background: #FFBA03;
    margin: auto;
    
    padding-top: 70px;
    padding-left: 116px;
    text-align: left;
}
.ShapkaSnacks {
    display: grid;
    grid-template-columns: 4fr 1fr 1fr;
}
.SnacksTitle {
    margin: 0px;
    color: #FFF;
    font-family: Neucha;
    font-size: 96px;
    font-style: normal;
    font-weight: 400;
    /*line-height: 143.412%;  137.675px */
}
.logoSnacks_1 {
    /*width: 439px;
    height: 674px;
    flex-shrink: 0;
    border-radius: 32px;
    background: #D9D9D9;*/
    align-self: top;
    justify-self: center;
    width: 236px;
    height: 236px;
    background-blend-mode: color;
}
.logoSnacks_2 {
    /*width: 439px;
    height: 674px;
    flex-shrink: 0;
    border-radius: 32px;
    background: #D9D9D9;*/
    position: absolute;
    z-index: 1000;
    align-self: top;
    justify-self: right;
    margin-right: 70px;
    width: 270px;
    height: 270px;
    background-blend-mode: color;  
}
.SnacksText {
    margin-top: 0px;
    color: #FFF;
    font-family: Inter;
    font-size: 40px;
    font-style: normal;
    font-weight: 500;
    /*line-height: 143.412%;  57.365px */

}
.SnacksUrls {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    grid-template-rows: 1fr 1fr;
    margin-top: 140px;
/*    margin-right: 90px;*/
    
}
.SnackWrapper {
    width: 256px;
    height: 251px;
    border-radius: 40px;
    background: #D9D9D9;
    text-align: center;

}
.SnackWrapper p {
    margin-top: 130px;
    color: #000;
    font-family: Inter;
    font-size: 32px;
    font-style: normal;
    font-weight: 400;
    line-height: 143.412%; /* 45.892px */
}
.SnackWrapperAbove {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
/*    position: absolute;
    z-index: 1000;*/
    margin-top: -400px;
    width: 256px;
    height: 251px;
}
</style>