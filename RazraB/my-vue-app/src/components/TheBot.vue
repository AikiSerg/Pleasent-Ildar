<template>
    <div class="Bot">
        <div class="ShapkaBot">
            <p class="BotTitle">
                Бот
            </p>
        </div>
        <p class="BotText">
            А если ты не знаешь, что выбрать, то поделись своим <br>
            настроением, и я помогу тебе выбрать видео и закуски
        </p> 
        <div class="VideosUrls">
            <div class="VideoWrapperLogobot"><img src="../assets/Botlogo.png"></div>
            <div class="VideoWrapper"> </div>
            <div class="VideoWrapperUrlBot"><a href="https://t.me/unpleasent"><p>Открыть чат Бот</p></a></div>
        </div>      
    </div>
</template>

<script>
export default {
    name: 'TheBot',
    props: {
        msg: String
    }
}
</script>
    
<style>
  /* Вставьте ваш CSS код здесь */
.Bot {
/*    width: 1440px; */
    height: 861px;
    background:#FDFBF7;
    margin: auto;
    
    padding-top: 70px;
/*    padding-left: 116px;*/
    text-align: left;
}
.ShapkaBot {
    display: grid;
    grid-template-columns: 1fr 1fr;
    margin-left: 116px;
}
.BotTitle {
    margin: 0px;
    color: #FFB901;
    font-family: Neucha;
    font-size: 96px;
    font-style: normal;
    font-weight: 400;
    /*line-height: 143.412%;  137.675px */
}

.BotText {
    margin-top: 0px;
    margin-left: 116px;
    color: #FFB901;
    font-family: Inter;
    font-size: 40px;
    font-style: normal;
    font-weight: 500;
    /*line-height: 143.412%;  57.365px */

}
.VideosUrls {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    margin-top: 80px;
 /*   margin-right: 90px;*/
    
}
.VideoWrapperLogobot a img {
    width: 520.006px;
    height: 648.708px;
    background: lightgray 50% / cover no-repeat;
    border-radius: 31px;

}
.VideoWrapperUrlBot {
    margin-top: 190px;
}

.VideoWrapperUrlBot a {
    text-decoration: none;
}
.VideoWrapperUrlBot a p {
    display: grid;
    text-align: center;
    align-items: center;
    align-self: end;
    width: 569px;
    height: 190.525px;
    border-radius: 37.762px;
    background: #FFB901;
    color: #FFF;
    font-family: Inter;
    font-size: 48px;
    font-style: normal;
    font-weight: 400;
    line-height: 143.412%; /* 68.838px */


}
</style>