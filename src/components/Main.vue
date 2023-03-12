<template>
    <div>
        <div class="main__top">
            <h2 class="title">Обо мне</h2>
            <div class="container">
                <div class="main__top-box">
                <div class="main__top-left">
                        <img src="../assets/images/photo.jpg" alt="" class="main__img">
                    </div>
                    <div class="main__top-right">
                        <h3 class="main__right-title">Зубенко Михаил Петрович</h3>
                        <p class="main__right-text">Я могу делать семейные портреты в студии, работать на показах мод, снимать моделей для рекламы или фотографировать на свадьбах. Отдельное направление -- съёмки предметов и еды, которые заказывают для рекламы или меню ресторанов. Я могу быть криминальным фотографом мест преступлений, охотником за знаменитостями или снимать диких животных для журналов о природе. Я востребованный специалист в новостных изданиях, работаю в паре с журналистом и могу оказаться где угодно: от гламурной вечеринки до места пожара, наводнения и даже вооруженного конфликта. Моя профессия будет востребована и в будущем, ведь 80% успеха фотографии -- это не качество техники, а профессионализм фотографа. </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style >
.main__top {
    background: #0E1C25;
}
.container {
    width: 1140px;
    margin: 0 auto;
}
.title {
    text-align: center;
    font-weight: 700;
    font-size: 40px;
    line-height: 46px;
    color: #FFFFFF;
    padding: 35px;
}
.main__top-box {
    display: flex;
    gap: 106px;
}
.main__right-title {
    font-weight: 400;
    font-size: 35px;
    line-height: 40px;
    color: #FFFFFF;
}
.main__right-text {
    font-weight: 400;
    font-size: 18px;
    line-height: 21px;
    text-align: justify;
    color: #FFFFFF;
    width: 466px;
    height: 397px;
}
.main__top-right {
    display: flex;
    flex-direction: column;
    gap: 64px;
    margin-top: 50px;
}
.main__img {
    padding-bottom: 100px;
}
</style>