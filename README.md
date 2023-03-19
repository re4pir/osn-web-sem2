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
    <!--footer-->
<footer class="footer">
    <div class="footer__container">
      <div div class="footer__context flex">
        <div class="footer__left">
          <a href="#" class="footer__left-nubmer">8 800 000 00 00</a>
          <p class="footer__left-time">Рады слышать вас с 9:00 до 21:00</p>
          <ul class="footer__left-item-list list-reset flex">
            <li>
              <a href="https://facebook.com" class="footer__left-item">
                <img src="/src/img/facebook.svg" alt="">
              </a>
            </li>
            <li>
              <a href="https://vk.com" class="footer__left-item">
                <img src="/src/img/vk.svg" alt="">
              </a>
            </li>
            <li>
              <a href="https://instagram.com" class="footer__left-item">
                <img src="/src/img/inst.svg" alt="">
              </a>
            </li>
          </ul>
        </div>
        <div class="footer__middle">
          <ul class="footer__middle-list list-reset">
            <li>
              <a href="#" class="footer__middle-list-item">Политика конфиденциальности</a>
            </li>
            <li>
              <a href="#" class="footer__middle-list-item">Заявка на оформление договора/налоговый отчет</a>
            </li>
            <li>
              <a href="#" class="footer__middle-list-item">Договор-Оферта</a>
            </li>
            <li>
              <a href="#" class="footer__middle-list-item">Сведения об образовательной организации</a>
            </li>
          </ul>
        </div>
        <div class="footer__right-list flex">
          <a href="" class="footer__right-list-item"></a>
          <a href="" class="footer__right-list-item"></a>
        </div>
      </div>
    </div>
</footer>
