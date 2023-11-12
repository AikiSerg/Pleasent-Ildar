<template>
    <div class="footer">
        <p class="socialnetwork">
            Я в соц. сетях
        </p>
    </div>
</template>

<script>
export default {
    name: 'TheFooter',
    props: {
        msg: String
    }
}
</script>
    
<style>
  /* Вставьте ваш CSS код здесь */
.footer {
/*    width: 1440px; */
    height: 547px;
    border-radius: 85px 85px 0px 85px;
    background: #FFB901;
    margin: auto;
    display: grid;
    grid-template-columns: 2fr 1fr;
    padding-top: 90px;
    padding-left: 116px;
    text-align: left;
}
.socialnetwork {
    color: #FFF;
    font-family: Neucha;
    font-size: 92px;
    font-style: normal;
    font-weight: 400;
    line-height: 143.412%; /* 131.939px */
    }
</style>