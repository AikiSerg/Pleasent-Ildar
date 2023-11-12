<template>
    <div class="Video">
        <div class="ShapkaVideo">
            <p class="VideoTitle">
                Видео
            </p>
            <div class="logoVideo">
                <img src="../assets/logoVideo.png">
            </div>
        </div>
        <p class="VideoText">
            Что ты можешь посмотреть на моем канале:
        </p> 
        <div class="VideosUrls">
            <div class="VideoWrapper"><a href="https://www.youtube.com/watch?v=jMfrWa0wuTw"><img src="../assets/mqdefault_6s.webp"></a></div>
            <div class="VideoWrapper"><a href="https://www.youtube.com/watch?v=2B9FdXWsz7s"><img src="../assets/mqdefault_6s (1).webp"></a></div>
            <div class="VideoWrapper"><a href="https://www.youtube.com/watch?v=EOxOBRMjLdY"><img src="../assets/mqdefault_6s (2).webp"></a></div>
        </div>      
    </div>
</template>

<script>
export default {
    name: 'TheVideo',
    props: {
        msg: String
    }
}
</script>
    
<style>
  /* Вставьте ваш CSS код здесь */
.Video {
/*    width: 1440px; */
    height: 861px;
    background:#FDFBF7;
    margin: auto;
    
    padding-top: 70px;
    padding-left: 116px;
    text-align: left;
}
.ShapkaVideo {
    display: grid;
    grid-template-columns: 1fr 1fr;
}
.VideoTitle {
    margin: 0px;
    color: #FFB901;
    font-family: Neucha;
    font-size: 96px;
    font-style: normal;
    font-weight: 400;
    /*line-height: 143.412%;  137.675px */
}
.logoVideo {
    /*width: 439px;
    height: 674px;
    flex-shrink: 0;
    border-radius: 32px;
    background: #D9D9D9;*/
    
    align-self: top;
    justify-self: center;
    width: 180.178px;
    height: 179.634px;
    transform: rotate(6.567deg);
    flex-shrink: 0;
    background: lightgray 50% / cover no-repeat;
}
.VideoText {
    margin-top: 0px;
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
    margin-right: 90px;
    
}
.VideoWrapper a img {

    border-radius: 31px;

}
</style>