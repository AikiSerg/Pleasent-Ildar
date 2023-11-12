<template>
    <div class="header">
        <p class="aboutMe">
            Привет! Я Ильдар, и я здесь, <br>
            чтобы скрасить твой вечер <br>
            классным контентом и <br>
            вкусной едой
        </p>
        <div class="logoaboutMe">
            <img src="../assets/logo2.png">
        </div>
    </div>
</template>

<script>
export default {
    name: 'TheHeader',
    props: {
        msg: String
    }
}
</script>
    
<style>
  /* Вставьте ваш CSS код здесь */
.header {
/*    width: 1440px; */
    height: 861px;
    border-radius: 0px 0px 85px 85px;
    background: #FFB901;
    margin: auto;
    display: grid;
    grid-template-columns: 2fr 1fr;
    padding-top: 170px;
    padding-left: 116px;
    text-align: left;
}
.aboutMe {
    color: #FFF;
    text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    font-family: Neucha;
    font-size: 64px;
    font-style: normal;
    font-weight: 400;
    line-height: 140%; /* 89.6px */
}
.logoaboutMe {
    width: 439px;
    height: 674px;
    flex-shrink: 0;
    border-radius: 32px;
    background: #D9D9D9;
}
.header > p {
    color: #fff;
    font-family: 'Neucha', Arial, sans-serif;
    font-size: 55px;
}
</style>