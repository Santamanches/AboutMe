<template>
  <div class="hello">
    <nav>
        
        <div class="header__nav">
        <div class="container">
            <div class="navbar">
                <a href="#" class="logo">PROWEB</a>
                <ul class='navbar__list'>
                    <li v-for="(link,i) in links" :key="i">
                        <a @click="$emit('send', link)" href="#" class="navbar__link">
                             {{ link }}
                         </a>
                     </li>
                </ul>
            </div>
            </div>
            </div>
            <div class="header__content">
                <h1 class="header__title">Добро пожаловать на мой сайт</h1>
                <a href="tel:+998907777777" class="header__call">Позвонить</a>
            </div>
        </nav>

  </div>
</template>

<script>
export default {
    data() {
        return {
            links: ['Обо мне','Мои работы','Контакты']
        }
    }
  }
</script>

<style scoped>
.container {
    width: 1140px;
    margin: 0 auto;
}
.header__nav {
    background: #000000;
;
}
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.logo {
    font-weight: 700;
    font-size: 40px;
    line-height: 46px;
    color: aliceblue;
    padding: 15px ;
}
.navbar__link {
    font-weight: 400;
    font-size: 25px;
    line-height: 29px;
    color: white;
}
.navbar__list {
    display: flex;
    gap: 79px;
}
.header__content {
    background-image: url(../assets/images/bg.jpg);
    height: 850px;
    display: flex;
    flex-direction: column;
    gap: 155px;
    align-items: center;
}
.header__title {
    padding-top: 300px;
    font-weight: 700;
    font-size: 40px;
    line-height: 46px;
    color: #000000;
}
.header__call {
    font-weight: 700;
    font-size: 35px;
    line-height: 40px;
    color: #000000;
    background: white;
    border-radius: 10px;
    padding: 10px 23px;
}

</style>
