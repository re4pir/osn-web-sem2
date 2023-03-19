# osn-web-sem2
<!--Задание№1-->
<human-body>
    <human-body__head></human-body__head>
    <human-body__torso></human-body__torso>
    <human-body__left-arm>
        <human-body__left-arm_tattoo></human-body__left-arm_tattoo>
    </human-body__left-arm>
    <human-body__right-arm>
        <human-body__right-arm_wrist>
            <human-body__right-arm_wrist_ring></human-body__right-arm_wrist_ring>
        </human-body__right-arm_wrist>
    </human-body__right-arm>
    <human-body__left-leg></human-body__left-leg>
    <human-body__right-leg></human-body__right-leg>
</human-body>
<!--Задание№2-->
<!--header-->
<header class="header">
    <div class="header__container container">
      <div class="header__context flex">
        <a href="index.html">
          <img class="header__logo" src="/src/img/header__img.svg" alt="header-img" class="header__img">
        </a>
        <nav class="header__nav nav flex">
          <ul class="nav-first list-reset flex">
            <li class="nav-first__item">
              <a href="#" class="nav-first__link">О&nbsp;нас</a>
            </li>
            <li class="nav-first__item">
              <a href="#enjoy" class="nav-first__link">Enjoy</a>
            </li>
            <li class="nav-first__item">
              <a href="#cost" class="nav-first__link">Программы и&nbsp;цены</a>
            </li>
            <li class="nav-first__item">
              <a href="#" class="nav-first__link">Филиалы</a>
            </li>
          </ul>
          <ul class="nav-second list-reset flex">
            <li class="nav-second__item">
              <a href="demo.html" class="nav-second__link">Demo</a>
            </li>
            <li class="nav-second__item">
              <a href="form.html" class="nav-second__link">Form</a>
            </li>
          </ul>
        </nav>
				<button class="header__btn modal__open">
					Бесплатный урок
				</button>
      </div>
    </div>
  </header>
  <!--form-->
  <section class="form">
        <div class="form__container">
            <div class="form__context">
                <form action="//httpbin.org/post" method="post" class="form__form">
                    <h2 class="form__form-template">Запишитесь на бесплатный пробный урок</h2>
                    <p class="form__form-subtemplate">Личная информация</p>
                    <input type="text" required placeholder="Ваше имя" class="form__form-item">
                    <input type="text" placeholder="Ваша дата рождения" class="form__form-item">
                    <select class="form__form-item">
                        <option hidden value="" selected>Ваш пол</option>
                        <option>Мужской</option>
                        <option>Женский</option>
                        <option>Другой</option>
                    </select>
                    <p class="form__form-subtemplate">Контактные данные</p>
                    <input type="text" required placeholder="Ваш номер телефона" class="form__form-item">
                    <input type="text" required placeholder="Ваш пароль" class="form__form-item" id="req">
                    <input type="text" required placeholder="Ваш Email" class="form__form-item">
                    <select class="form__form-item" required>
                        <option value hidden selected>Выберите удобное вам время</option>
                        <option>9:00-11:00</option>
                        <option>11:00-13:00</option>
                        <option>13:00-15:00</option>
                        <option>15:00-17:00</option>
                        <option>17:00-19:00</option>
                        <option>19:00-21:00</option>
                    </select>
                    <input type="reset" value="Ввести заного" class="form__form-btn-reset btn-reset" disabled>
                    <input type="submit" value="Попробывать бесплатно" class="form__form-btn-submit btn-reset">
                </form>
            </div>
        </div>
    </section>
    <!--card-->
          <li class="section-study__list-item">
            <div class="loader-box">
              <span class="loader"></span>
            </div>
            <p class="section-study__list-item--template--foruth">Lorem ipsum dolor sit.</p>
            <p class="section-study__list-item--decr">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Veniam,
              suscipit. Fuga, dignissimos eius. Corporis non perspiciatis sint dolor.</p>
          </li>
    <!--section-promotions-->
    <section class="section-promotions">
      <div class="section-promotions__containter container">
        <div class="section-promotions__context">
          <h2 class="section-promotions__template">А так же бесплатно для всех учеников</h2>
          <ul class="section-promotions__list list-reset flex">
            <li class="section-promotions__list-item">
              <p class="section-promotions__list-item-text">Тестирование в течении всего периода обучения</p>
            </li>
            <li class="section-promotions__list-item">
              <p class="section-promotions__list-item-text">Бесплатные тематические мероприятия</p>
            </li>
            <li class="section-promotions__list-item">
              <p class="section-promotions__list-item-text">Приложение с онлайн тренажером для запоминания новых
                слов</p>
            </li>
            <li class="section-promotions__list-item">
              <p class="section-promotions__list-item-text">Платформа с интерактивными упражнениями с
                автоматической проверкой&nbsp;ответов&nbsp;и&nbsp;электронным дневником достижений</p>
            </li>
            <li class="section-promotions__list-item">
              <p class="section-promotions__list-item-text">Cертификат&nbsp;по&nbsp;окончанию&nbsp;обучения</p>
            </li>
            <li class="section-promotions__list-item">
              <p class="section-promotions__list-item-text">Налоговый вычет 13%</p>
            </li>
          </ul>
        </div>
      </div>
    </section>
<!--Задание№3-->
<!--header-->
header.header>div.header__container.container>div.header__context.flex>a>img.header__logo^nav.header__nav.nav.flex>ul.nav-first.list-reset.flex>li.nav-first-item*4>a.nav-first__link^^ul.nav-second.list-reset.flex>li.nav-second__item*2>a.nav-second__link^^^button.header__btn.modal__open
![Иллюстрация к проекту]()
<!--form-->
section.form>div.form__container>div.form__context>form.form__form>(h2.form__form-template^p.form__form-subtemplate+input.form__form-item*2^select.form__form-item>option*4^^p.form__form-subtemplate+input.form__form-item*3^select.form__form-item>option*7^^input.form__form-btn-reset.btn-reset^input.form__form-btn-submit.btn-reset)>
<!--card-->
li.section-study__list-item>(div.loader-box>span.loader^^p.section-study__list-item--template--fourth^p.section-study__list-item--descr)>
<!--section-promotions-->
    section.section-promotions>div.section-promotions__containter.container>div.section-promotions__context>h2.section-promotions-template+ul.section-promotions__list.list-reset.flex>li.section-promotions__list-item*6>p.section-promotions__list-item-text