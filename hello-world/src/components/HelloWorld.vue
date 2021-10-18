<template>
  
  
  
   <div class="page">


        <header>



            <div class="container">
                <div class="head">
                    <div class="left">
                        <div style="display: flex; align-items: center; justify-content: space-evenly;">
                            <h1 style="text-transform: uppercase;">kassir.kz</h1>
                            <img src="Vector (3).png" alt="" style="position: relative; left: 65px;"><input type="search" class="input" name="search" id="" placeholder="Артисты, мероприятия, концерты">
                        </div>

                        <div class="links">
                            <a href="" class="link"> Концерты</a>
                            <a href="" class="link">Театры</a>
                            <a href="" class="link">Спорт</a>
                            <a href="" class="link">Мастер-классы</a>
                            <a href="" class="link">Детям</a>
                            <a href="" class="link">Туры</a>
                        </div>
                    </div>

                    <div class="right" style="display: flex; align-items: center; height: 80px">






                        <div class="ava" style="display: flex; 
        align-items: space-between;
        flex-direction: column;
        ">
                            <div style="display: flex; 
            align-items: center; 
            justify-content: space-between;
            
            ">
                                <div class="f f-vcenter">
                                    <p>Ру </p>
                                    <img style="margin-top: 9px;" height="6px" src="Icon.png" alt="icon">
                                </div>

                                <div class="switch-body">
                                    <input class="switch" type="checkbox" name="lang" id="lang">
                                </div>


                                <div> <img src="Vector.png" alt=""></div>
                                <div>
                                    <div class="circle">
                                    </div>
                                    <p>Алишер</p>
                                </div>




                            </div>
                            <div style="display: flex;">

                                <div><img src=" Group.png " style="display: inline "> Алматы <img style="margin-top: 9px; " height="6px " src="Icon.png " alt="icon " >
                                </div>

                                <div><img src="Group (1).png " style="display: inline; margin-left: 10px; "> Сегодня <img style="margin-top: 9px; " height="6px " src="Icon.png " alt="icon " >
                                </div>

                            </div>

                        </div>


                    </div>
                </div>
            </div>
        </header>

        <main class="main ">
            <div class="container ">
                <div class=" main_content f ">
                    <div class="main_item ">

                      <div class="container">
                        <div class="circle "></div>
                        <h2>Алишер Кожахметов</h2>
                        <p>email@com</p>
                        <div class="user_info ">
                            <a href=" " class="link active ">
                            Личные данные
                        </a>
                            <a href=" " class="link ">
                            Билеты
                        </a>
                            <a href=" " class="link ">
                            Бонусы
                        </a>

                            <a href=" " class="link ">
                            Избранное
                        </a>
                            <a href=" " class="link ">
                            Выход
                        </a>
                        </div>

                    </div>
                    <div class="main_item-1 ">
                        <div>
                            <h2>Личные данные</h2>
                            <p>Ваше имя, почта и пароль</p>


                        </div>

                        <div class="user_mail">
                            <div>
                                <h3>Имя и аватар</h3>
                                <div class="circle "></div>
                                <h2>Алишер Кожахметов</h2>
                            </div>


                            <button class="btn">Изменить</button>

                        </div>

                        <div class="user_sex ">
                            <h3>Пол</h3>
                            <label for="sex ">Мужской</label><input type="radio" name="sex " id="sex">
                            <label for="sex2 ">Женский</label><input type="radio" name="sex " id="sex2 ">
                        </div>

                        <div class="user_mail">
                            <div>
                                <h3>Почта</h3>
                                hebecik340@mtlcz.com
                            </div>
                            <button class="btn">Изменить</button>
                        </div>

                        <div class=" user_pass ">
                            <div>
                                <h3>Почта</h3>
                                hebecik340@mtlcz.com
                            </div>
                            <button class="btn">Изменить</button>
                        </div>

                        <div class="user_city ">
                            <div>
                                <h3>Почта</h3>
                                hebecik340@mtlcz.com
                            </div>
                            <button class="btn">Изменить</button>
                        </div>

                    </div>

</div>
                </div>
            </div>
        </main>

        <footer class="footer ">

            <div class="footer_child ">
                <div class="footer__level1 ">
                    <div>
                        <h3>Подпишитесь на рассылку</h3>
                        <p>Ежемесячная рассылка главных новостей, мероприятий и анонсов.</p>
                    </div>


                    

                    <input placeholder="Почта " type="email " class="input" name="email " id=" ">
                    <button class="btn ">Подписаться</button>

                </div>


                <div class="footer__level2 ">
                    <div>
                        <h3>Скачайте приложение</h3>
                        <p>Десятки людей скачивают kassir.kz ежеднево и улучшают свою жизнь.</p>
                    </div>



                    <div>
                        <h3>Сервис</h3>
                        Покупка билетов<br> Возврат билетов<br> Служба поддержки<br> О сервисе<br> Новости
                    </div>
                    <div>
                        <h3>Организаторам</h3>
                        Условия участия<br> Билетная система<br> Корпоративным клиентам
                    </div>
                    <div>
                        <h3>Соцсети</h3>
                        Инстаграм<br> Фейсбук
                        <br> ВКонтакте
                    </div>
                </div>

                <div style="margin-top: 20px">
                    <p>© 2005–2021 Kassir.kz</p>

                    <a href=" " class="link ">Публичная оферта</a>
                    <a href=" " class="link ">Политика конфиденциальности</a>
                </div>

            </div>

        </footer>
    </div>
</template>

<script>
import axios from 'axios'
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  mounted() {
   axios.get('dev.kassir.kz/api/users/:id ', { /* Может быть так указать в express так параметры указывают в endpoints */
     headers: {
       authorization: 'Bearer 1|3iL54oDS99Uc9dlZiMXIHixUoWgs0G7jIgV9N1Gw'
     }
   })

      axios.get('dev.kassir.kz/api/users ', {
        params: {
          id:  12345
        },
     headers: {
       authorization: 'Bearer 1|3iL54oDS99Uc9dlZiMXIHixUoWgs0G7jIgV9N1Gw'
     }
   })
  }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    /* Указываем box sizing */
    
    *,
    *::before,
    *::after {
        box-sizing: border-box;
    }
    /* Убираем внутренние отступы */
    
    ul[class],
    ol[class] {
        padding: 0;
    }
    /* Убираем внешние отступы */
    
    body,
    h1,
    h2,
    h3,
    h4,
    p,
    ul[class],
    ol[class],
    li,
    figure,
    figcaption,
    blockquote,
    dl,
    dd {
        margin: 0;
    }
    /* Выставляем основные настройки по-умолчанию для body */
    
    body {
        min-height: 100vh;
        scroll-behavior: smooth;
        text-rendering: optimizeSpeed;
        line-height: 1.5;
    }
    /* Удаляем стандартную стилизацию для всех ul и il, у которых есть атрибут class*/
    
    ul[class],
    ol[class] {
        list-style: none;
    }
    /* Элементы a, у которых нет класса, сбрасываем до дефолтных стилей */
    
    a:not([class]) {
        text-decoration-skip-ink: auto;
    }
    /* Упрощаем работу с изображениями */
    
    img {
        max-width: 100%;
    }
    /* Указываем понятную периодичность в потоке данных у article*/
    
    article>*+* {
        margin-top: 1em;
    }
    /* Наследуем шрифты для инпутов и кнопок */
    
    input,
    button,
    textarea,
    select {
        font: inherit;
    }
    /* Удаляем все анимации и переходы для людей, которые предпочитай их не использовать */
    
    @media (prefers-reduced-motion: reduce) {
        * {
            animation-duration: 0.01ms !important;
            animation-iteration-count: 1 !important;
            transition-duration: 0.01ms !important;
            scroll-behavior: auto !important;
        }
    }
    
    .dropdown {
        display: flex;
        align-items: center;
    }
    
    .container {
        max-width: 1600px;
        margin: auto;
        padding: 15px;
    }
    
    .page {
        max-width: 1600px;
        margin: auto;
        padding: 25px;
        display: flex;
        flex-direction: column;
        min-height: 100%;
        font-family: 'Courier New', Courier, monospace;
    }
    /************************Header**********************/
    
    .switch-body {
        background: #EDEDED;
        width: 70px;
        height: 40px;
        position: relative;
        border-radius: 40%;
    }
    
    .switch {
        background: white;
        appearance: none;
        border-radius: 50%;
        display: block;
        height: 30px;
        width: 30px;
        z-index: 5;
        position: absolute;
        top: 0;
        left: 0;
    }
    
    .head {
        width: 100%;
        height: 100px;
    }
    
    .head {
        display: flex;
        justify-content: space-between;
        padding: 16px 92px;
        flex-wrap: wrap;
    }
    
    .link {
        text-decoration: none;
        color: black;
        margin-left: 5px;
        margin-top: 24px;
    }
    
    .link,
    button {
        cursor: pointer;
    }

    .links {
      display: flex;
      justify-content: space-between;
      margin-top: 20px;
      flex-wrap: wrap;
    }
    
    h1 {
        display: inline-block;
    }
    
    .input {
        display: inline-block;
        width: 397px;
        height: 45px;
        border: 0.5px solid rgba(0, 0, 0, 0.2);
        padding: 20px 10px 16px 35px;
        border-radius: 8px;
        margin-left: 40px;
    }
    
    .f {
        display: flex;
    }
    
    .f-center {
        justify-content: center;
    }
    
    .fv-center {
        align-items: center;
    }
    
    .circle {
        background: #EDEDED;
        width: 35px;
        height: 35px;
        border-radius: 100%;
    }
    /************8****End Header**************************/
    /**********************Main***********************/
    
    .user_info {
      
        display: flex;
        flex-direction: column;
        background: #EDEDED66;
        width: 290px;
        height: 264px;
        padding: 24px;
    }
    
    .active {
        color: gray
    }
    
    .user_mail,
    .user_city,
    .user_pass {
        display: flex;
        justify-content: space-between;
    }
    
    .user_mail .btn,
    .user_city .btn,
    .user_pass .btn {
        margin-left: 614px;
        margin-top: 15px;
    }
    
    main {
        flex-grow: 1;
    }

    .main_item-1,   .main_item {
      margin-top: 58px;
    }
    
    .main_content {
        justify-content: space-around;
    }
    /***************************************************/
    /**********************Foooter***********************/
    
    .footer {
        width: 100%;
        margin-top: 200px;
    }
    
    .footer_child {
        padding: 43px 94px;
        background: #EDEDED;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }
    
    .footer__level1 {
        display: flex;
        justify-content: space-between;
        border-bottom: gray 1px solid;
        padding-bottom: 30px;
        flex-flow: wrap;
    }
    
    .footer__level2 {
        display: flex;
        justify-content: space-between;
        flex-flow: row wrap;
        margin-top: 43px;
    }
    
    .footer__level2 div {
        display: flex;
        flex-direction: column;
        margin-top: 20px;
    }
    
    .btn {
        background: #000000;
        padding: 3px 10px 5px;
        border-radius: 8px;
        width: 215.06px;
        height: 50px;
        color: rgb(247, 236, 236)
    }
    /***************************************************/


@media (max-width:  758px) 
{
  .container, 
   .page, 
   .user_city, 
   .user_mail, 
   .user_pass 
   {
    max-width: 720px;
  }

  
} 
</style>
