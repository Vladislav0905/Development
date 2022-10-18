# Development
Blanchard-gallery


<!DOCTYPE html>
<html lang="ru">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" href="img/blanchard.png">
    <link rel="stylesheet" href="https://unpkg.com/tippy.js@6/animations/scale.css">
    <link rel="stylesheet" href="https://unpkg.com/simplebar@latest/dist/simplebar.css">
    <link rel="stylesheet" href="css/choices.min.css">
    <link rel="stylesheet" href="css/swiper-bundle.min.css">
    <link rel="stylesheet" href="css/normalize.css">
    <link rel="stylesheet" href="css/style.css">

    <title>Blanchard-Художественная галерея</title>
</head>

<body>
    <header class="header">
        <div class="header-top">
            <div class="container header__container">
                <button aria-label="Открыть меню" class="btn-reset header__burger header__burger-open">
                        <span class="header__burger-line"></span>
                    </button>
                <a class="header-top__logo">
                    <picture>
                        <source srcset="img/header-logo-320.svg" media="(max-width:474px)">
                        <source srcset="img/header-logo-768.svg" media="(max-width:992px)">
                        <source srcset="img/header-logo-1024.svg" media="(max-width:1024px)">
                        <img class="header-top__logo-img" src="img/header-logo.svg" alt="Логотип Blanchard Художественная галерея">
                    </picture>
                </a>
                <nav class="header-nav nav flex">
                    <ul class="list-reset header-nav__list flex">
                        <li class="header-nav__item">
                            <a href="#about" class=" site-text header-nav__item-link js-scroll-link link-condition">О&nbsp;нас</a>
                        </li>
                        <li class="header-nav__item">
                            <a href="#gallery" class="site-text header-nav__item-link js-scroll-link link-condition">Галерея</a>
                        </li>
                        <li class="header-nav__item">
                            <a href="#catalog" class="site-text header-nav__item-link js-scroll-link link-condition">Каталог</a>
                        </li>
                        <li class="header-nav__item">
                            <a href="#events" class="site-text header-nav__item-link js-scroll-link link-condition">События</a>
                        </li>
                        <li class="header-nav__item">
                            <a href="#projects" class="site-text header-nav__item-link js-scroll-link link-condition">Проекты</a>
                        </li>
                        <li class="header-nav__item">
                            <a href="#contacts" class="site-text header-nav__item-link  js-scroll-link link-condition">Контакты</a>
                        </li>
                    </ul>
                    <a href="#" class="link-lk login-enter link-condition" aria-label="Войти в личный кабинет">
                        <span class="link-lk__arrow-wrap">
                                <svg class="link-lk__arrow-svg"
                                    width="18"
                                    height="13"
                                    viewbox="0 0 18 13"
                                    fill="none"
                                    xmlns="http://www.w3.org/2000/svg">
                                    <path class="link-lk__arrow-svg-path" d="M9.62056 9.09278L10.6389 10.1111L14.25 6.5L10.6389 2.88889L9.62056 3.90722L11.4839 5.77778H0V7.22222H11.4839L9.62056 9.09278ZM16.0556 0H5.94444C5.14278 0 4.5 0.65 4.5 1.44444V4.33333H5.94444V1.44444H16.0556V11.5556H5.94444V8.66667H4.5V11.5556C4.5 12.35 5.14278 13 5.94444 13H16.0556C16.85 13 17.5 12.35 17.5 11.5556V1.44444C17.5 0.65 16.85 0 16.0556 0Z" fill="white"/>
                                </svg>
                          </span> Войти
                    </a>
                </nav>
                <button type="button" class="header__search-btn btn-reset" aria-label="Найти">
                        <svg
                            class="header__search-btn-icon"
                            width="30"
                            height="29"
                            viewbox="0 0 30 29"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg">
                            <rect
                                width="9.15446"
                                height="2.28862"
                                transform="matrix(-0.718931 0.695081 0.718931 0.695081 6.58154 21.0461)"
                                fill="white"/>
                            <path
                                fill-rule="evenodd"
                                clip-rule="evenodd"
                                d="M16.1246 24.174C10.0376 24.174 5.32763 19.2726 5.32763 13.5104C5.32763 7.74823 10.0376 2.84676 16.1246 2.84676C22.2115 2.84676 26.9215 7.74823 26.9215 13.5104C26.9215 19.2726 22.2115 24.174 16.1246 24.174ZM16.1246 26.8399C8.76285 26.8399 2.79502 20.8721 2.79502 13.5104C2.79502 6.14869 8.76285 0.180847 16.1246 0.180847C23.4863 0.180847 29.4541 6.14869 29.4541 13.5104C29.4541 20.8721 23.4863 26.8399 16.1246 26.8399Z"
                                fill="white"/>
                        </svg>
                    </button>
                <form class="form js-form">
                    <button type="submit" class="form__search-loop btn-reset" aria-label="Поиск по сайту">
                            <svg class="form__search-loop-svg"
                                width="30"
                                height="29"
                                viewbox="0 0 30 29"
                                fill="none"
                                xmlns="http://www.w3.org/2000/svg">
                                <rect
                                    width="9.15446"
                                    height="2.28862"
                                    transform="matrix(-0.718931 0.695081 0.718931 0.695081 6.58154 21.0461)"
                                    fill="white"/>
                                <path
                                    fill-rule="evenodd"
                                    clip-rule="evenodd"
                                    d="M16.1246 24.174C10.0376 24.174 5.32763 19.2726 5.32763 13.5104C5.32763 7.74823 10.0376 2.84676 16.1246 2.84676C22.2115 2.84676 26.9215 7.74823 26.9215 13.5104C26.9215 19.2726 22.2115 24.174 16.1246 24.174ZM16.1246 26.8399C8.76285 26.8399 2.79502 20.8721 2.79502 13.5104C2.79502 6.14869 8.76285 0.180847 16.1246 0.180847C23.4863 0.180847 29.4541 6.14869 29.4541 13.5104C29.4541 20.8721 23.4863 26.8399 16.1246 26.8399Z"
                                    fill="white"/>
                            </svg>
                        </button>
                    <input class="form__input" type="text" name="text">
                    <button type="button" class="form__search-close btn-reset" aria-label="Закрыть поиск">
                            <span class="form__search-close-line"></span>
                        </button>
                </form>
            </div>
        </div>
        <div class="header-btm">
            <div class="container header__container-btm">
                <ul class="list-reset main-list">
                    <li class="main-item">
                        <button class="main-item-btn link-condition js-header-dropdown-btn site-text btn-reset" data-path="one" aria-label="Выбор художников в разделе реализм">
                                Реализм
                                <span class="dropdown-btn-arrow"></span>
                            </button>
                        <div class="main-dropdown js-header-drop" data-target="one">
                            <div class="main-dropdown-wrap" data-simplebar>
                                <ul class="list-reset main-drop-list">
                                    <li class="main-dropdown-item">
                                        <a href="#" class="main-item-link tintoretto">Тинторетто</a>
                                    </li>
                                    <li class="main-dropdown-item">
                                        <a href="#" class="main-item-link fridrih">Фридрих</a>
                                    </li>
                                    <li class="main-dropdown-item">
                                        <a href="#" class="main-item-link leonardo">Леонардо</a>
                                    </li>
                                    <li class="main-dropdown-item">
                                        <a href="#" class="main-item-link veroco">Верроккьо</a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </li>
                    <li class="main-item">
                        <button class="main-item-btn link-condition js-header-dropdown-btn site-text btn-reset" data-path="two" aria-label="Выбор художников в разделе импрессионизм">
                                Импрессионизм
                                <span class="dropdown-btn-arrow"></span>
                            </button>
                        <div class="main-dropdown js-header-drop" data-target="two">
                            <div class="main-dropdown-wrap" data-simplebar>
                                <ul class="list-reset main-drop-list">
                                    <li class="main-dropdown-item">
                                        <a href="#" class="main-item-link mone">Моне</a>
                                    </li>
                                    <li class="main-dropdown-item">
                                        <a href="#" class="main-item-link sisley">Сислей</a>
                                    </li>
                                    <li class="main-dropdown-item">
                                        <a href="#" class="main-item-link mane">Мане</a>
                                    </li>
                                    <li class="main-dropdown-item">
                                        <a href="#" class="main-item-link renuar">Ренуар</a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </li>
                    <li class="main-item">
                        <button class="main-item-btn link-condition js-header-dropdown-btn site-text btn-reset" data-path="three" aria-label="Выбор художников в разделе постимпрессионизм">
                                Постимпрессионизм
                                <span class="dropdown-btn-arrow"></span>
                            </button>
                        <div class="main-dropdown js-header-drop" data-target="three">
                            <div class="main-dropdown-wrap" data-simplebar>
                                <ul class="list-reset main-drop-list">
                                    <li class="main-dropdown-item">
                                        <a href="#" class="main-item-link vangog">Ван Гог</a>
                                    </li>
                                    <li class="main-dropdown-item">
                                        <a href="#" class="main-item-link sezan">Сезанн</a>
                                    </li>
                                    <li class="main-dropdown-item">
                                        <a href="#" class="main-item-link gogen">Гоген</a>
                                    </li>
                                    <li class="main-dropdown-item">
                                        <a href="#" class="main-item-link sera">Сёра</a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </li>
                    <li class="main-item">
                        <button class="main-item-btn link-condition js-header-dropdown-btn site-text btn-reset" data-path="four" aria-label="Выбор художников в разделе авангард">
                                Авангард
                                <span class="dropdown-btn-arrow"></span>
                            </button>
                        <div class="main-dropdown js-header-drop" data-target="four">
                            <div class="main-dropdown-wrap" data-simplebar>
                                <ul class="list-reset main-drop-list">
                                    <li class="main-dropdown-item">
                                        <a href="#" class="main-item-link kand">Кандинский</a>
                                    </li>
                                    <li class="main-dropdown-item">
                                        <a href="#" class="main-item-link marinetti">Маринетти</a>
                                    </li>
                                    <li class="main-dropdown-item">
                                        <a href="#" class="main-item-link malevich">Малевич</a>
                                    </li>
                                    <li class="main-dropdown-item">
                                        <a href="#" class="main-item-link picasso">Пикассо</a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </li>
                    <li class="main-item">
                        <button class="main-item-btn link-condition js-header-dropdown-btn site-text btn-reset" data-path="five" aria-label="Выбор художников в разделе футуризм">
                                Футуризм
                                <span class="dropdown-btn-arrow"></span>
                            </button>
                        <div class="main-dropdown js-header-drop" data-target="five">
                            <div class="main-dropdown-wrap" data-simplebar>
                                <ul class="list-reset main-drop-list">
                                    <li class="main-dropdown-item">
                                        <a href="#" class="main-item-link karra">Карра</a>
                                    </li>
                                    <li class="main-dropdown-item">
                                        <a href="#" class="main-item-link pratella">Прателла</a>
                                    </li>
                                    <li class="main-dropdown-item">
                                        <a href="#" class="main-item-link severini">Северини</a>
                                    </li>
                                    <li class="main-dropdown-item">
                                        <a href="#" class="main-item-link balla">Балла</a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </li>
                </ul>
                <form action="#" method="post" class="header__form">
                    <button type="submit" class="header__form-btn  btn-reset" aria-label="Найти">
                            <svg
                                class="header__form-icon"
                                width="22"
                                height="22"
                                fill="none"
                                xmlns="http://www.w3.org/2000/svg"
                            >
                                <rect
                                    width="6.8678"
                                    height="1.71695"
                                    transform="matrix(-0.718931 0.695081 0.718931 0.695081 4.9375 15.6534)"
                                    fill="white"
                                />
                                <path
                                    fill-rule="evenodd"
                                    clip-rule="evenodd"
                                    d="M12.0969 18C7.53041 18 3.99692 14.3229 3.99692 10C3.99692 5.67715 7.53041 2 12.0969 2C16.6634 2 20.1969 5.67715 20.1969 10C20.1969 14.3229 16.6634 18 12.0969 18ZM12.0969
20C6.57408 20 2.09692 15.5228 2.09692 10C2.09692 4.47715 6.57408 0 12.0969 0C17.6198 0 22.0969 4.47715 22.0969 10C22.0969 15.5228 17.6198 20 12.0969 20Z"
                                    fill="white"
                                />
                            </svg>
                        </button>
                    <input type="text" placeholder="Поиск по сайту" class="header__form-search site-text">
                </form>
            </div>
        </div>
    </header>
    <main class="main">
        <section class="hero">
            <h1 class="visually-hidden">Blanchard-Художественная галерея</h1>
            <div class="swiper hero__swiper">
                <div class="swiper-wrapper swiper-container slider">
                    <div class="swiper-slide swiper-slide--1"></div>
                    <div class="swiper-slide swiper-slide--2"></div>
                    <div class="swiper-slide swiper-slide--3"></div>
                </div>
            </div>
            <div class="container hero__container">
                <div class="hero__content">
                    <h2 class="hero__title">Прикоснитесь к&nbsp;прекрасному</h2>
                    <p class="hero__descr">
                        Мы&nbsp;вынуждены отталкиваться от&nbsp;того, что реализация намеченных плановых заданий создаёт предпосылки для&nbsp;новых предложений
                    </p>
                    <a class="hero__link js-scroll-link" href="#contacts">Подписаться на&nbsp;рассылку</a>
                </div>
            </div>
        </section>
        <section class="about-us" id="about">
            <div class="container about-us__container">
                <h2 class="about-us__title">О&nbsp;нас</h2>
                <p class="about-us__descr">
                    Ясность нашей позиции очевидна: семантический разбор внешних противодействий однозначно определяет каждого участника как&nbsp;способного принимать собственные решения касаемо распределения внутренних резервов и&nbsp;ресурсов. Не&nbsp;следует, однако,
                    забывать, что высококачественный прототип будущего проекта влечёт за&nbsp;собой процесс внедрения и&nbsp;модернизации модели развития. Повседневная практика показывает, что высокое качество позиционных исследований создаёт необходимость
                    включения в&nbsp;производственный план целого ряда внеочередных мероприятий с&nbsp;учётом комплекса распределения внутренних резервов и&nbsp;ресурсов. В&nbsp;рамках спецификации современных стандартов, действия представителей оппозиции
                    набирают популярность среди определённых слоёв населения, а&nbsp;значит, должны быть разоблачены.
                </p>
            </div>
        </section>
        <section class="gallery" id="gallery">
            <div class="container gallery__container">
                <div class="gallery__castom">
                    <h2 class="gallery__title">Галерея</h2>
                    <div class="gallery__filter-block">
                        <h3 class="gallery__subtitle">Фильтр:</h3>
                        <select class="filter-gallery-select" name="select" id="selectCustom" aria-label="Выбор изобразительного искусства">
                                <option value="Живопись">Живопись</option>
                                <option value="Рисунок">Рисунок</option>
                                <option value="Скульптура">Скульптура</option>
                            </select>
                    </div>
                    <ul class="gallery__list list-reset">
                        <li class="gallery__item">
                            <label class="gallery__label">
                                    <input
                                        class="gallery__checkbox"
                                        type="checkbox"
                                        name="check"
                                        aria-label="Девятнадцатый век"
                                    >
                                    <span class="gallery__custom-checkbox"></span>
                                    <span class="gallery__checkbox-text">XIX век</span>
                                </label>
                        </li>
                        <li class="gallery__item">
                            <label class="gallery__label">
                                    <input
                                        class="gallery__checkbox"
                                        type="checkbox"
                                        name="check"
                                        aria-label="Двадцатый век"
                                    >
                                    <span class="gallery__custom-checkbox"></span>
                                    <span class="gallery__checkbox-text">XX век</span>
                                </label>
                        </li>
                        <li class="gallery__item">
                            <label class="gallery__label">
                                    <input
                                        class="gallery__checkbox"
                                        type="checkbox"
                                        name="check"
                                        aria-label="Современность"
                                    >
                                    <span class="gallery__custom-checkbox"></span>
                                    <span class="gallery__checkbox-text">Современность</span>
                                </label>
                        </li>
                    </ul>
                </div>
                <div class="gallery__slider-container">
                    <div class="gallery__slider-top">
                        <button class="gallery__swiper-button-next btn-next" aria-label="Предыдущий слайд"></button>
                        <div class="swiper-pagination"></div>
                        <button class="gallery__swiper-button-prev btn-prev" aria-label="Следующий слайд"></button>
                    </div>
                    <div class="gallery__swiper">
                        <ul class="swiper-wrapper gallery__swiper-item list-reset">
                            <li class="swiper-slide gallery-slide" data-path="modal">
                                <a class="btn-reset swiper-slide__btn" href="#" aria-label="Выбор картины">
                                    <picture>
                                        <source srcset="img/gallery/gallery-slide-1-320.jpg" media="(max-width: 510px)">
                                        <source srcset="img/gallery/gallery-slide-1-768.jpg" media="(max-width: 992px)">
                                        <source srcset="img/gallery/gallery-slide-1-1024.jpg" media="(max-width: 1024px)">
                                        <img class="swiper-slide__img" src="img/gallery/gallery-slide-1.jpg" alt="Картина художника">
                                    </picture>
                                </a>
                            </li>
                            <li class="swiper-slide gallery-slide" data-path="modal">
                                <a class="btn-reset swiper-slide__btn" href="#" aria-label="Выбор картины">
                                    <picture>
                                        <source srcset="img/gallery/gallery-slide-2-320.jpg" media="(max-width: 510px)">
                                        <source srcset="img/gallery/gallery-slide-2-768.jpg" media="(max-width: 992px)">
                                        <source srcset="img/gallery/gallery-slide-2-1024.jpg" media="(max-width: 1024px)">
                                        <img class="swiper-slide__img" src="img/gallery/gallery-slide-2.jpg" alt="Картина художника">
                                    </picture>
                                </a>
                            </li>
                            <li class="swiper-slide gallery-slide" data-path="modal">
                                <a class="btn-reset swiper-slide__btn" aria-label="Выбор картины">
                                    <picture>
                                        <source srcset="img/gallery/gallery-slide-3-320.jpg" media="(max-width: 510px)">
                                        <source srcset="img/gallery/gallery-slide-3-768.jpg" media="(max-width: 992px)">
                                        <source srcset="img/gallery/gallery-slide-3-1024.jpg" media="(max-width: 1024px)">
                                        <img class="swiper-slide__img" src="img/gallery/gallery-slide-3.jpg" alt="Картина художника">
                                    </picture>
                                </a>
                            </li>
                            <li class="swiper-slide gallery-slide" data-path="modal">
                                <a class="btn-reset swiper-slide__btn" href="#" aria-label="Выбор картины">
                                    <picture>
                                        <source srcset="img/gallery/gallery-slide-4-320.jpg" media="(max-width: 510px)">
                                        <source srcset="img/gallery/gallery-slide-4-768.jpg" media="(max-width: 992px)">
                                        <source srcset="img/gallery/gallery-slide-4-1024.jpg" media="(max-width: 1024px)">
                                        <img class="swiper-slide__img" src="img/gallery/gallery-slide-4.jpg" alt="Картина художника">
                                    </picture>
                                </a>
                            </li>
                            <li class="swiper-slide gallery-slide" data-path="modal">
                                <a class="btn-reset swiper-slide__btn" href="#" aria-label="Выбор картины">
                                    <picture>
                                        <source srcset="img/gallery/gallery-slide-5-320.jpg" media="(max-width: 510px)">
                                        <source srcset="img/gallery/gallery-slide-5-768.jpg" media="(max-width: 992px)">
                                        <source srcset="img/gallery/gallery-slide-5-1024.jpg" media="(max-width: 1024px)">
                                        <img class="swiper-slide__img" src="img/gallery/gallery-slide-5.jpg" alt="Картина художника">
                                    </picture>
                                </a>
                            </li>
                            <li class="swiper-slide gallery-slide" data-path="modal">
                                <a class="btn-reset swiper-slide__btn" href="#" aria-label="Выбор картины">
                                    <picture>
                                        <source srcset="img/gallery/gallery-slide-6-320.jpg" media="(max-width: 510px)">
                                        <source srcset="img/gallery/gallery-slide-6-768.jpg" media="(max-width: 992px)">
                                        <source srcset="img/gallery/gallery-slide-6-1024.jpg" media="(max-width: 1024px)">
                                        <img class="swiper-slide__img" src="img/gallery/gallery-slide-6.jpg" alt="Картина художника">
                                    </picture>
                                </a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="modal">
                <div class="modal__container" data-target="modal">
                    <button class="modal-close link-condition btn-reset">
                            <svg
                                width="16"
                                height="16"
                                viewbox="0 0 16 16"
                                fill="none"
                                xmlns="http://www.w3.org/2000/svg"
                            >
                                <path
                                    fill-rule="evenodd"
                                    clip-rule="evenodd"
                                    d="M0.666641 15.3043L15.3333 3.17761e-05L16 0.695679L1.33331 15.9999L0.666641 15.3043Z"
                                    fill="black"
                                />
                                <path
                                    fill-rule="evenodd"
                                    clip-rule="evenodd"
                                    d="M0.666725 -2.96187e-06L15.3334 15.3042L14.6667 15.9999L5.76143e-05 0.695644L0.666725 -2.96187e-06Z"
                                    fill="black"
                                />
                            </svg>
                        </button>
                    <div class="modal__wrap">
                        <div class="modal__content">
                            <picture class="modal__picture">
                                <source srcset="img/modal-gallery/modal-320.jpg" media="(max-width: 767px)">
                                <source srcset="img/modal-gallery/modal-768.jpg" media="(max-width: 768px)">
                                <source srcset="img/modal-gallery/modal-1024.jpg" media="(max-width: 1024px)">
                                <img class="modal__img" src="img/modal-gallery/modal-1920.jpg" alt="Картина Женщина с граблями">
                            </picture>
                            <div class="modal__text">
                                <h3 class="modal__title">Казимир Малевич</h3>
                                <p class="modal__subtitle">&laquo;Женщина с&nbsp;граблями&raquo;</p>
                                <span class="modal__dates">1931–1932</span>
                                <p class="modal__descr">
                                    Картина из&nbsp;второй серии крестьянского цикла работ Казимира Малевича. Художник принялся за&nbsp;её&nbsp;создание в&nbsp;1930&ndash;1931&nbsp;годах, после того, как первый цикл был утерян после Берлинской и&nbsp;Варшавской выставок в&nbsp;1927&nbsp;году.
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="catalog" id="catalog">
            <div class="container">
                <h2 class="catalog__title">Каталог</h2>
                <p class="catalog-text">
                    Акционеры крупнейших компаний, которые представляют собой яркий пример континентально-европейского типа политической культуры, будут объявлены нарушающими общечеловеческие нормы этики и&nbsp;морали. Являясь всего лишь частью общей картины, стремящиеся
                    вытеснить традиционное производство, нанотехнологии и&nbsp;по&nbsp;сей день остаются уделом либералов, которые жаждут быть функционально разнесены на&nbsp;независимые элементы.
                </p>

                <div class="catalog__wrap js-tabs-wrap">
                    <div class="catalog__content-wrap">
                        <div class="catalog__painter-info active js-tab-content" id="domenico" data-target="domenico">
                            <picture>
                                <source srcset="img/catalog/domenico-320.jpg" media="(max-width: 320px)">
                                <source srcset="img/catalog/domenico-768.jpg" media="(max-width: 992px)">
                                <source srcset="img/catalog/domenico-1024.jpg" media="(max-width: 1024px)">
                                <img class="painter-img" src="img/catalog/domenico.jpg" alt="Доменико Гирландайо">
                            </picture>
                            <h3 class="painter-title">Доменико Гирландайо</h3>
                            <span class="painter-content-time">2 июня 1448 — 11 января 1494</span>
                            <p class="painter-descr">
                                Один из&nbsp;ведущих флорентийских художников Кватроченто, основатель художественной династии, которую продолжили его&nbsp;брат Давид и&nbsp;сын Ридольфо. Глава художественной мастерской, где юный Микеланджело в&nbsp;течение года овладевал профессиональными
                                навыками. Автор фресковых циклов, в&nbsp;которых выпукло, со&nbsp;всевозможными подробностями показана домашняя жизнь библейских персонажей (в&nbsp;их&nbsp;роли выступают знатные граждане Флоренции в&nbsp;костюмах того&nbsp;времени).
                            </p>
                        </div>
                        <div class="catalog__painter-info js-tab-content" id="benedetto" data-target="benedetto">
                            <picture>
                                <source srcset="img/catalog/benedetto-320.jpg" media="(max-width: 320px)">
                                <source srcset="img/catalog/benedetto-768.jpg" media="(max-width: 992px)">
                                <source srcset="img/catalog/benedetto-1024.jpg" media="(max-width: 1024px)">
                                <img class="painter-img" src="img/catalog/benedetto.jpg" alt="Бенедетто ди Биндо">
                            </picture>
                            <h3 class="painter-title">Бенедетто ди&nbsp;Биндо</h3>
                            <span class="painter-content-time"> ок 1380-85 — 19 сентября 1417</span>
                            <p class="painter-descr">
                                Бенедетто ди&nbsp;Биндо остался в&nbsp;истории искусства как сиенский художник, так сказать, &laquo;второго ряда&raquo;, несмотря на&nbsp;то, что за&nbsp;свою короткую жизнь он&nbsp;выполнил ряд весьма престижных заказов, включая работы в&nbsp;Сиенском
                                соборе (работы в&nbsp;главном соборе республики второстепенным художникам не&nbsp;поручались). Обучение он&nbsp;прошёл у&nbsp;Таддео ди&nbsp;Бартоло, крупного сиенского мастера поздней готики, в&nbsp;боттеге которого Бенедетто
                                трудился вместе с&nbsp;Грегорио ди&nbsp;Чекко. Наибольшее влияние на&nbsp;его творчество оказали работы Симоне Мартини, в&nbsp;частности в&nbsp;выборе колорита, а&nbsp;тонко проработанные лица его персонажей напоминают
                                произведения Джованни да&nbsp;Милано.
                            </p>
                        </div>
                        <div class="catalog__painter-info js-tab-content" id="ambrogio" data-target="ambrogio">
                            <picture>
                                <source srcset="img/catalog/benedetto-320.jpg" media="(max-width: 320px)">
                                <source srcset="img/catalog/benedetto-768.jpg" media="(max-width: 992px)">
                                <source srcset="img/catalog/benedetto-1024.jpg" media="(max-width: 1024px)">
                                <img class="painter-img" src="img/catalog/ambrogio.jpg" alt="Санта Лючия">
                            </picture>
                            <h3 class="painter-title">Амброджо Бергоньоне</h3>
                            <span class="painter-content-time"> 1453 — 1523</span>
                            <p class="painter-descr">
                                Хотя он&nbsp;был почти современником Леонардо да&nbsp;Винчи, он&nbsp;рисовал в&nbsp;стиле, более близком к&nbsp;доренессансному, ломбардскому искусству Винченцо Фоппа и&nbsp;Бернардино Зенале. Даты его рождения и&nbsp;смерти неизвестны; он, как говорят,
                                родился в&nbsp;Фоссано в&nbsp;Пьемонте, и&nbsp;его название объясняется его художественной принадлежностью к&nbsp;бургундской школе. Его слава в&nbsp;основном связана с&nbsp;его работой в&nbsp;комплекс Чертоза ди&nbsp;Павия,
                                состоящий из&nbsp;церкви и&nbsp;монастыря картезианцев. Вряд&nbsp;ли он&nbsp;спроектировал в&nbsp;1473 году знаменитый фасад самой Чертозы. Он&nbsp;проработал там восемь лет, начиная с&nbsp;1486&nbsp;года, в&nbsp;сотрудничестве
                                со&nbsp;своим братом Бернардино Бергоньоне, когда он&nbsp;предоставил эскизы фигур Богородицы, святых и&nbsp;апостолов для хоровых прилавков, выполненные в&nbsp;тарсии или инкрустированные инкрустацией. работал по&nbsp;дереву
                                до&nbsp;1494&nbsp;г., когда вернулся в&nbsp;Милан. Только одна известная картина, алтарь в&nbsp;базилике Сант-Эусторджо, с&nbsp;большой вероятностью может быть отнесена к&nbsp;периоду его карьеры ранее 1486&nbsp;года.
                            </p>
                        </div>
                        <div class="catalog__painter-info js-tab-content" id="bissolo" data-target="bissolo">
                            <img class="painter-img" src="img/catalog/bissolo.jpg" alt="Франческо Биссоло">
                            <h3 class="painter-title">Франческо Биссоло</h3>
                            <span class="painter-content-time">1470 или 1472 - 20 апреля 1554 </span>
                            <p class="painter-descr">
                                Сын художника. Ученик Джованни Беллини. С&nbsp;1490 переехал в&nbsp;мастерскую Беллини. С&nbsp;1492 по&nbsp;1530 год работал в&nbsp;Венеции. Помогал учителю в&nbsp;работе над украшением Большого зала Совета Дворца дожей (Венеция). Принимал участие в&nbsp;создании
                                украшений Церкви Иль Реденторе в&nbsp;Венеции. Художник эпохи Возрождения. В&nbsp;своём творчестве подражал Джорджоне. Работы художника хранятся ныне во&nbsp;многих музеях мира. В&nbsp;санкт-петербургском Эрмитаже находится
                                его картина &laquo;Богоматерь с&nbsp;Младенцем Христом&raquo;. В&nbsp;Британской Национальной галерее&nbsp;&mdash; &laquo;Мадонна с&nbsp;Младенцем со&nbsp;святыми и&nbsp;донатором&raquo;. Ряд его полотен находится в&nbsp;музеях
                                Варшавы, Лос-Анджелеса (Музей Нортона Саймона и&nbsp;Los Angeles County Museum of&nbsp;Art), Дэйтоновском институте искусств (штат Огайо, США) и&nbsp;др.
                            </p>
                        </div>
                        <div class="catalog__painter-info js-tab-content" id="giovanni" data-target="giovanni">
                            <img class="painter-img" src="img/catalog/giovanni.jpg" alt="Джованни Антонио Больтраффио">
                            <h3 class="painter-title">Джованни Больтраффио</h3>
                            <span class="painter-content-time">1466 или 1467— 1516</span>
                            <p class="painter-descr">
                                Вазари сообщает, что художник происходил из&nbsp;аристократической семьи. Воспитанный в&nbsp;традициях Фоппы, Бернардо Дзенале и&nbsp;Амброджо Бергоньоне, он&nbsp;прошёл обучение в&nbsp;мастерской Леонардо. Его первое произведение &laquo;Воскресение Христа,
                                святой Леонард и&nbsp;святая Лючия&raquo; выполнено в&nbsp;1491 году совместно с&nbsp;Марко д&rsquo;Оджоно для миланской церкви Сан-Джованни-сул-Муро. Был придворным художником Лодовико Моро и&nbsp;славился своими психологическими
                                портретами. Больтраффио умер в&nbsp;возрасте 49&nbsp;лет и&nbsp;был похоронен на&nbsp;кладбище церкви Св. Паулы в&nbsp;Комито. Историки искусства предполагают, что фигура Младенца на&nbsp;картине Леонардо да&nbsp;Винчи
                                &laquo;Мадонна Литта&raquo; принадлежит кисти Джованни Антонио Больтраффио. Известны подготовительные рисунки Больтраффио, в&nbsp;точности воспроизводящие эту фигуру.
                            </p>
                        </div>
                        <div class="catalog__painter-info js-tab-content" id="francesco" data-target="francesco">
                            <img class="painter-img" src="img/catalog/francesco.jpg" alt="Франческо Бонсиньори">
                            <h3 class="painter-title">Франческо Бонсиньори</h3>
                            <span class="painter-content-time">1460 — 2 июля 1519</span>
                            <p class="painter-descr">
                                Родился около 1460 года в&nbsp;Вероне в&nbsp;семье художника Альберто Бонсиньори. Обучался живописи в&nbsp;мастерской Франческо Бенальо. В&nbsp;1480 году переехал из&nbsp;Вероны в&nbsp;Венецию, где жил до&nbsp;1487&nbsp;года. В&nbsp;ранний период творчества
                                находился под влиянием венецианской живописной школы. Особенное впечатление на&nbsp;Бонсиньори оказало творчество Антонелло да&nbsp;Мессины, Джованни Беллини, Чима да&nbsp;Конельяно и&nbsp;Альвизе Виварини. Среди известных
                                творений этого периода самыми ранними произведениями художника являются полотна &laquo;Мадонна со&nbsp;спящим младенцем&raquo; 1483 года и&nbsp;&laquo;Алтарь Даль Бово&raquo;, или &laquo;Мадонна на&nbsp;троне с&nbsp;предстоящими
                                святыми и&nbsp;донатором Альтабеллой Авогадро&raquo; 1484&nbsp;года, которые ныне входят в&nbsp;собрание Общественного музея Вероны.
                            </p>
                        </div>
                        <div class="catalog__painter-info js-tab-content" id="empty" data-target="empty">
                            <img class="painter-img" src="img/catalog/unknow-painter.jpg" alt="Здесь будет художник.">
                            <h3 class="painter-title">Что мы&nbsp;о&nbsp;нём знаем?</h3>
                            <p class="painter-descr painter-descr-unknow">
                                Пока ничего... Зато мы&nbsp;точно знаем, что в&nbsp;галерее есть на&nbsp;что посмотреть!
                            </p>
                            <a href="#gallery" class="painter-content-link js-scroll-link">В галерею</a>
                        </div>
                    </div>
                    <ul class="list-reset catalog__accordion accordion reset-list js-accordion-container">
                        <li class="accordion__question ac js-enabled">
                            <button class="accordion__heading ac-trigger" aria-label="С тысячи четырёхсотого по тысяча четыреста девяносто девятый годы">
                                    <span class="accordion__heading-text">
                                        <span class="accordion__heading-text-wrap">
                                            C 1400 по 1499 гг
                                        </span>
                                    </span>
                                    <svg
                                        class="head-icon"
                                        width="50"
                                        height="50"
                                        viewbox="0 0 50 50"
                                        fill="none"
                                        xmlns="http://www.w3.org/2000/svg">
                                        <path
                                            class="head-icon-round"
                                            d="M49 25C49 11.7452 38.2548 1.00001 25 1.00001C11.7452 1.00001 1 11.7452 1 25C1 38.2548 11.7452 49 25 49C38.2548 49 49 38.2548 49 25Z"
                                            fill="#ECECEC"
                                            stroke="#ECECEC"
                                            stroke-width="2"/>
                                        <path d="M33.3333 26.6667L25 18.3333L16.6667 26.6667" stroke="black"/>
                                    </svg>
                                </button>
                            <div class="accordion__content ac-panel">
                                <div class="accordion__content-wrap">
                                    <ul class="list-reset accordion__inner-list reset-list">
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="benedetto" href="#benedetto">
                                                <span class="link__text">Бенедетто ди Биндо</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="ambrogio" href="#ambrogio">
                                                <span class="link__text">Бергоньоне, Амброджо</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="bissolo" href="#bissolo">
                                                <span class="link__text">Биссоло, Франческо</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="giovanni" href="#giovanni">
                                                <span class="link__text">Больтраффио, Джованни</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="francesco" href="#francesco">
                                                <span class="link__text">Бонсиньори, Франческо</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="empty" href="#epmty">
                                                <span class="link__text">Боттичини, Рафаэлло</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="empty" href="#epmty">
                                                <span class="link__text">Брамантино</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="empty" href="#epmty">
                                                <span class="link__text">Бреа, Людовико</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="empty" href="#epmty">
                                                <span class="link__text">Бьяджо д’Антонио Туччи</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="empty" href="#epmty">
                                                <span class="link__text">Веккьетта</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="empty" href="#epmty">
                                                <span class="link__text">Андреа Верроккьо</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link active" data-path="domenico" href="#domenico">
                                                <span class="link__text">Доменико Гирландайо</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="empty" href="#empty">
                                                <span class="link__text">Беноццо Гоццоли</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="empty" href="#empty">
                                                <span class="link__text">Граначчи, Франческо</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="empty" href="#empty">
                                                <span class="link__text">Грегорио ди Чекко</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="empty" href="#empty">
                                                <span class="link__text">Джованни да Удине</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="empty" href="#empty">
                                                <span class="link__text">Джованни ди Паоло</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="empty" href="#empty">
                                                <span class="link__text">Джорджоне</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="empty" href="#empty">
                                                <span class="link__text">Парентино, Бернардо</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="empty" href="#empty">
                                                <span class="link__text">Пезеллино</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="empty" href="#empty">
                                                <span class="link__text">Пьетро Перуджино</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="empty" href="#empty">
                                                <span class="link__text">Перуцци, Бальдассаре</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="empty" href="#empty">
                                                <span class="link__text">Пизанелло</span>
                                            </a>
                                        </li>
                                        <li class="accordion__item">
                                            <a class="accordion__painter-link link link--text js-tab-btn js-scroll-link " data-path="empty" href="#empty">
                                                <span class="link__text">Пинтуриккьо</span>
                                            </a>
                                        </li>
                                    </ul>
                                </div>
                            </div>
                        </li>
                        <li class="accordion__question ac js-enabled">
                            <button class="accordion__heading ac-trigger" aria-label="С тысячи пятисотого по тысяча пятьсот девяносто девятый годы">
                                    <span class="accordion__heading-text">
                                        <span class="accordion__heading-text-wrap">C 1500 по 1599 гг</span>
                                    </span>
                                    <svg
                                        class="head-icon"
                                        width="50"
                                        height="50"
                                        viewbox="0 0 50 50"
                                        fill="none"
                                        xmlns="http://www.w3.org/2000/svg"
                                    >
                                        <path
                                            class="head-icon-round"
                                            d="M49 25C49 11.7452 38.2548 1.00001 25 1.00001C11.7452 1.00001 1 11.7452 1 25C1 38.2548 11.7452 49 25 49C38.2548 49 49 38.2548 49 25Z"
                                            fill="#ECECEC"
                                            stroke="#ECECEC"
                                            stroke-width="2"
                                        />
                                        <path d="M33.3333 26.6667L25 18.3333L16.6667 26.6667" stroke="black"/>
                                    </svg>
                                </button>
                            <div class="accordion__content ac-panel">
                                <div class="accordion__content-unknow flex">
                                    <div class="accordion__content-left"></div>
                                    <div class="accordion__content-right">
                                        <h3 class="accordion__content-title">Здесь пока пусто</h3>
                                        <p class="accordion__content-descr">
                                            А&nbsp;в&nbsp;галерее вы&nbsp;всегда можете найти что-то интересное для себя
                                        </p>
                                        <a href="#gallery" class="accordion__content-link js-scroll-link">В галерею</a>
                                    </div>
                                </div>
                            </div>
                        </li>
                        <li class="accordion__question ac js-enabled">
                            <button class="accordion__heading ac-trigger" aria-label="С тысячи шестисотого по тысяча шестьсот девяносто девятый годы">
                                    <span class="accordion__heading-text">
                                        <span class="accordion__heading-text-wrap">C 1600 по 1699 гг</span>
                                    </span>
                                    <svg
                                        class="head-icon"
                                        width="50"
                                        height="50"
                                        viewbox="0 0 50 50"
                                        fill="none"
                                        xmlns="http://www.w3.org/2000/svg"
                                    >
                                        <path
                                            class="head-icon-round"
                                            d="M49 25C49 11.7452 38.2548 1.00001 25 1.00001C11.7452 1.00001 1 11.7452 1 25C1 38.2548 11.7452 49 25 49C38.2548 49 49 38.2548 49 25Z"
                                            fill="#ECECEC"
                                            stroke="#ECECEC"
                                            stroke-width="2"
                                        />
                                        <path d="M33.3333 26.6667L25 18.3333L16.6667 26.6667" stroke="black"/>
                                    </svg>
                                </button>
                            <div class="accordion__content ac-panel">
                                <div class="accordion__content-unknow flex">
                                    <div class="accordion__content-left"></div>
                                    <div class="accordion__content-right">
                                        <h3 class="accordion__content-title">Здесь пока пусто</h3>
                                        <p class="accordion__content-descr">
                                            А&nbsp;в&nbsp;галерее вы&nbsp;всегда можете найти что-то интересное для себя
                                        </p>
                                        <a href="#gallery" class="accordion__content-link js-scroll-link">В галерею</a>
                                    </div>
                                </div>
                            </div>
                        </li>
                        <li class="accordion__question ac js-enabled">
                            <button class="accordion__heading ac-trigger" aria-label="С тысячи семисотого по тысяча семьсот девяносто девятый годы">
                                    <span class="accordion__heading-text">
                                        <span class="accordion__heading-text-wrap">C 1700 по 1799 гг</span>
                                    </span>
                                    <svg
                                        class="head-icon"
                                        width="50"
                                        height="50"
                                        viewbox="0 0 50 50"
                                        fill="none"
                                        xmlns="http://www.w3.org/2000/svg"
                                    >
                                        <path
                                            class="head-icon-round"
                                            d="M49 25C49 11.7452 38.2548 1.00001 25 1.00001C11.7452 1.00001 1 11.7452 1 25C1 38.2548 11.7452 49 25 49C38.2548 49 49 38.2548 49 25Z"
                                            fill="#ECECEC"
                                            stroke="#ECECEC"
                                            stroke-width="2"
                                        />
                                        <path d="M33.3333 26.6667L25 18.3333L16.6667 26.6667" stroke="black"/>
                                    </svg>
                                </button>
                            <div class="accordion__content ac-panel">
                                <div class="accordion__content-unknow flex">
                                    <div class="accordion__content-left"></div>
                                    <div class="accordion__content-right">
                                        <h3 class="accordion__content-title">Здесь пока пусто</h3>
                                        <p class="accordion__content-descr">
                                            А&nbsp;в&nbsp;галерее вы&nbsp;всегда можете найти что-то интересное для себя
                                        </p>
                                        <a href="#gallery" class="accordion__content-link js-scroll-link">В галерею</a>
                                    </div>
                                </div>
                            </div>
                        </li>
                        <li class="accordion__question ac js-enabled">
                            <button class="accordion__heading ac-trigger" aria-label="С тысячи восьмисотого по тысяча восемьсот девяносто девятый годы">
                                    <span class="accordion__heading-text">
                                        <span class="accordion__heading-text-wrap">C 1800 по 1899 гг</span>
                                    </span>
                                    <svg
                                        class="head-icon"
                                        width="50"
                                        height="50"
                                        viewbox="0 0 50 50"
                                        fill="none"
                                        xmlns="http://www.w3.org/2000/svg"
                                    >
                                        <path
                                            class="head-icon-round"
                                            d="M49 25C49 11.7452 38.2548 1.00001 25 1.00001C11.7452 1.00001 1 11.7452 1 25C1 38.2548 11.7452 49 25 49C38.2548 49 49 38.2548 49 25Z"
                                            fill="#ECECEC"
                                            stroke="#ECECEC"
                                            stroke-width="2"
                                        />
                                        <path d="M33.3333 26.6667L25 18.3333L16.6667 26.6667" stroke="black"/>
                                    </svg>
                                </button>
                            <div class="accordion__content ac-panel">
                                <div class="accordion__content-unknow flex">
                                    <div class="accordion__content-left"></div>
                                    <div class="accordion__content-right">
                                        <h3 class="accordion__content-title">Здесь пока пусто</h3>
                                        <p class="accordion__content-descr">
                                            А&nbsp;в&nbsp;галерее вы&nbsp;всегда можете найти что-то интересное для себя
                                        </p>
                                        <a href="#gallery" class="accordion__content-link js-scroll-link">В галерею</a>
                                    </div>
                                </div>
                            </div>
                        </li>
                        <li class="accordion__question ac js-enabled">
                            <button class="accordion__heading ac-trigger" aria-label="С тысячи девятисотого по тысяча девятьсот девяносто девятый годы">
                                    <span class="accordion__heading-text">
                                        <span class="accordion__heading-text-wrap">C 1900 по 1999 гг</span>
                                    </span>
                                    <svg
                                        class="head-icon"
                                        width="50"
                                        height="50"
                                        viewbox="0 0 50 50"
                                        fill="none"
                                        xmlns="http://www.w3.org/2000/svg"
                                    >
                                        <path
                                            class="head-icon-round"
                                            d="M49 25C49 11.7452 38.2548 1.00001 25 1.00001C11.7452 1.00001 1 11.7452 1 25C1 38.2548 11.7452 49 25 49C38.2548 49 49 38.2548 49 25Z"
                                            fill="#ECECEC"
                                            stroke="#ECECEC"
                                            stroke-width="2"
                                        />
                                        <path d="M33.3333 26.6667L25 18.3333L16.6667 26.6667" stroke="black"/>
                                    </svg>
                                </button>
                            <div class="accordion__content ac-panel">
                                <div class="accordion__content-unknow flex">
                                    <div class="accordion__content-left"></div>
                                    <div class="accordion__content-right">
                                        <h3 class="accordion__content-title">Здесь пока пусто</h3>
                                        <p class="accordion__content-descr">
                                            А&nbsp;в&nbsp;галерее вы&nbsp;всегда можете найти что-то интересное для себя
                                        </p>
                                        <a href="#gallery" class="accordion__content-link js-scroll-link">В галерею</a>
                                    </div>
                                </div>
                            </div>
                        </li>
                        <li class="accordion__question ac js-enabled">
                            <button class="accordion__heading ac-trigger" aria-label="С двухтысячного года">
                                    <span class="accordion__heading-text">
                                        <span class="accordion__heading-text-wrap">C 2000 г</span>
                                    </span>
                                    <svg
                                        class="head-icon"
                                        width="50"
                                        height="50"
                                        viewbox="0 0 50 50"
                                        fill="none"
                                        xmlns="http://www.w3.org/2000/svg"
                                    >
                                        <path
                                            class="head-icon-round"
                                            d="M49 25C49 11.7452 38.2548 1.00001 25 1.00001C11.7452 1.00001 1 11.7452 1 25C1 38.2548 11.7452 49 25 49C38.2548 49 49 38.2548 49 25Z"
                                            fill="#ECECEC"
                                            stroke="#ECECEC"
                                            stroke-width="2"
                                        />
                                        <path d="M33.3333 26.6667L25 18.3333L16.6667 26.6667" stroke="black"/>
                                    </svg>
                                </button>
                            <div class="accordion__content ac-panel">
                                <div class="accordion__content-unknow flex">
                                    <div class="accordion__content-left"></div>
                                    <div class="accordion__content-right">
                                        <h3 class="accordion__content-title">Здесь пока пусто</h3>
                                        <p class="accordion__content-descr">
                                            А&nbsp;в&nbsp;галерее вы&nbsp;всегда можете найти что-то интересное для себя
                                        </p>
                                        <a href="#gallery" class="accordion__content-link js-scroll-link">В галерею</a>
                                    </div>
                                </div>
                            </div>
                        </li>
                    </ul>
                </div>
            </div>
        </section>
        <section class="events" id="events">
            <div class="container events__container">
                <h2 class="events__title">События</h2>
                <button class="events__btn events__button-prev btn-reset" aria-label="Предыдущий слайд"></button>
                <button class="events__btn events__button-next btn-reset" aria-label="К следующему слайд"></button>
                <div class="events__swiper">
                    <ul class="list-reset swiper-wrapper">
                        <li class="swiper-slide event">
                            <picture>
                                <source srcset="img/events/events-img-1-320.jpg" media="(max-width:320px)">
                                <source srcset="img/events/events-img-1-768.jpg" media="(max-width:768px)">
                                <source srcset="img/events/events-img-1-1024.jpg" media="(max-width:1024px)">
                                <img class="events__img" src="img/events/events-img-1.jpg" alt="Музей им. Щусева">
                            </picture>
                            <div class="event__item-content">
                                <div class="events__info">
                                    <span class="event__small-text">Музей им. Щусева</span>
                                    <span class="event__small-text">с&nbsp;20&nbsp;марта по&nbsp;30&nbsp;апреля</span>
                                </div>
                                <h3 class="event__subtitle">
                                    Книжная&nbsp;гравюра в живом восприятии
                                </h3>
                                <p class="event__descr">
                                    Один из&nbsp;ведущих флорентийских художников Кватроченто, основатель художественной династии, которую продолжили его&nbsp;брат Давид и&nbsp;сын&nbsp;Ридольфо
                                </p>
                                <a class="event__link-more link-parameters" href="">
                                    <span class="event__link-text">Подробнее</span>
                                </a>
                            </div>
                        </li>
                        <li class="swiper-slide event">
                            <picture>
                                <source srcset="img/events/events-img-2-320.jpg" media="(max-width:320px)">
                                <source srcset="img/events/events-img-2-768.jpg" media="(max-width:768px)">
                                <source srcset="img/events/events-img-2-1024.jpg" media="(max-width:1024px)">
                                <img class="events__img" src="img/events/events-img-2.jpg" alt="ММОМА">
                            </picture>
                            <div class="event__item-content">
                                <div class="events__info">
                                    <span class="event__small-text">ММОМА</span>
                                    <span class="event__small-text">24&nbsp;марта 19:00</span>
                                </div>
                                <h3 class="event__subtitle">
                                    &laquo;Открытая дискуссия&raquo;. Дмитрий Петров и&nbsp;Сергей Ильин.
                                </h3>
                                <p class="event__descr">
                                    Высокий уровень вовлечения представителей целевой аудитории является чётким доказательством простого факта
                                </p>
                                <a class="event__link-more link-parameters" href="">
                                    <span class="event__link-text">Подробнее</span>
                                </a>
                            </div>
                        </li>
                        <li class="swiper-slide event">
                            <picture>
                                <source srcset="img/events/events-img-3-320.jpg" media="(max-width:320px)">
                                <source srcset="img/events/events-img-3-768.jpg" media="(max-width:768px)">
                                <source srcset="img/events/events-img-3-1024.jpg" media="(max-width:1024px)">
                                <img class="events__img" src="img/events/events-img-3.jpg" alt="Еврейский музей">
                            </picture>
                            <div class="event__item-content">
                                <div class="events__info">
                                    <span class="event__small-text">Еврейский музей</span>
                                    <span class="event__small-text">с&nbsp;31&nbsp;марта по&nbsp;21&nbsp;апреля</span>
                                </div>
                                <h3 class="event__subtitle">
                                    Выставка &laquo;Формация 2020&raquo;
                                </h3>
                                <p class="event__descr">
                                    Идейные соображения высшего порядка, а&nbsp;также современная методология разработки играет важную роль в&nbsp;формировании глубокомысленных рассуждений
                                </p>
                                <a class="event__link-more link-parameters" href="">
                                    <span class="event__link-text">Подробнее</span>
                                </a>
                            </div>
                        </li>
                        <li class="swiper-slide event">
                            <picture>
                                <source srcset="img/events/events-img-4-320.jpg" media="(max-width:320px)">
                                <source srcset="img/events/events-img-4-768.jpg" media="(max-width:768px)">
                                <source srcset="img/events/events-img-4-1024.jpg" media="(max-width:1024px)">
                                <img class="events__img" src="img/events/events-img-4.jpg" alt="ММАМ">
                            </picture>
                            <div class="event__item-content">
                                <div class="events__info">
                                    <span class="event__small-text">ММАМ</span>
                                    <span class="event__small-text">с&nbsp;8&nbsp;апреля по&nbsp;20&nbsp;мая</span>
                                </div>
                                <h3 class="event__subtitle">
                                    Джон Винзор. Фотографии из&nbsp;серии &laquo;Метафора&raquo;
                                </h3>
                                <p class="event__descr">
                                    Один из&nbsp;ведущих флорентийских художников Кватроченто, основатель художественной династии, которую продолжили его брат Давид и&nbsp;сын Ридольфо
                                </p>
                                <a class="event__link-more link-parameters" href="">
                                    <span class="event__link-text">Подробнее</span>
                                </a>
                            </div>
                        </li>
                        <li class="swiper-slide event">
                            <picture>
                                <source srcset="img/events/events-img-5-320.jpg" media="(max-width:320px)">
                                <source srcset="img/events/events-img-5-768.jpg" media="(max-width:768px)">
                                <source srcset="img/events/events-img-5-1024.jpg" media="(max-width:1024px)">
                                <img class="events__img" src="img/events/events-img-5.jpg" alt="Третьяковка на Крымском валу">
                            </picture>
                            <div class="event__item-content">
                                <div class="events__info">
                                    <span class="event__small-text">Третьяковка на&nbsp;Крымском валу</span>
                                    <span class="event__small-text">с&nbsp;30&nbsp;марта по&nbsp;30&nbsp;апреля</span>
                                </div>
                                <h3 class="event__subtitle">
                                    XXIV Международная биеннале молодого искусства
                                </h3>
                                <p class="event__descr">
                                    Внезапно, реплицированные с&nbsp;зарубежных источников, современные исследования
                                </p>
                                <a class="event__link-more link-parameters" href="">
                                    <span class="event__link-text">Подробнее</span>
                                </a>
                            </div>
                        </li>
                    </ul>
                </div>
                <div class="events__swiper-pagination"></div>
            </div>
        </section>
        <section class="projects" id="projects">
            <div class="container projects__container">
                <h2 class="projects__title">Проекты</h2>
                <p class="projects__descr">
                    Предварительные выводы: постоянное информационно-пропагандистское обеспечение нашей деятельности однозначно фиксирует необходимость своевременного выполнения сверхзадачи. А&nbsp;ещё независимые государства смешаны с&nbsp;не&nbsp;уникальными данными до&nbsp;степени
                    совершённой неузнаваемости, из-за чего возрастает их&nbsp;статус бесполезности. Прежде всего, постоянное информационно-пропагандистское
                    <button id="tooltip-1" class="tooltip btn-reset" aria-label="Подсказка"></button> обеспечение нашей деятельности однозначно фиксирует необходимость экономической целесообразности принимаемых решений. И&nbsp;нет сомнений, что действия
                    представителей оппозиции могут быть рассмотрены
                    <button id="tooltip-2" class="tooltip btn-reset" aria-label="Подсказка"></button> исключительно в&nbsp;разрезе маркетинговых и&nbsp;финансовых
                    <button id="tooltip-3" class="tooltip btn-reset" aria-label="Подсказка"></button> предпосылок. Банальные, но&nbsp;неопровержимые выводы, а&nbsp;также представители современных социальных резервов призывают нас к&nbsp;новым свершениям,
                    которые, в&nbsp;свою очередь, должны быть смешаны с&nbsp;не&nbsp;уникальными данными до&nbsp;степени совершённой неузнаваемости. Подробнее:
                    <a href="" class="projects__link link-parameters link-text">blanchard-art.ru/projects</a>
                </p>
                <h3 class="projects__subtitle">Партнёры проектов:</h3>
                <div class="projects__slider">
                    <button class="projects__button-prev projects__prev"></button>
                    <div class="projects__swiper">
                        <ul class="list-reset swiper-wrapper">
                            <li class="swiper-slide projects__item">
                                <a href="" class="projects__item-link">
                                    <img class="projects__item-img" src="img/projects/freelands.png " alt="Логотип компании Freelands Foundation">
                                </a>
                            </li>
                            <li class="swiper-slide projects__item">
                                <a href="" class="projects__item-link">
                                    <img class="projects__item-img" src="img/projects/institute.png " alt="Логотип компании Institute for Contemporary Art">
                                </a>
                            </li>
                            <li class="swiper-slide projects__item">
                                <a href="" class="projects__item-link">
                                    <img class="projects__item-img" src="img/projects/workhouse.png  " alt="Логотип компании Workhouse ARTS CENTER">
                                </a>
                            </li>
                            <li class="swiper-slide projects__item">
                                <a href="" class="projects__item-link">
                                    <img class="projects__item-img" src="img/projects/1849wine.png " alt="Логотип компании 1849 wine co.">
                                </a>
                            </li>
                            <li class="swiper-slide projects__item">
                                <a href="" class="projects__item-link">
                                    <img class="projects__item-img" src="img/projects/hiscox.png " alt="Логотип компании HISCOX">
                                </a>
                            </li>
                            <li class="swiper-slide projects__item">
                                <a href="" class="projects__item-link">
                                    <img class="projects__item-img" src="img/projects/camden.png " alt="Логотип компании Camden arts centre">
                                </a>
                            </li>
                            <li class="swiper-slide projects__item">
                                <a href="" class="projects__item-link">
                                    <img class="projects__item-img" src="img/projects/stassen.png " alt="Логотип компании Stassen PREMIUM BELGIAN CIDER">
                                </a>
                            </li>
                            <li class="swiper-slide projects__item">
                                <a href="" class="projects__item-link">
                                    <img class="projects__item-img" src="img/projects/watts-gallery.png " alt="Логотип компании WATTS GALLERY ARTISTS' VILLAGE">
                                </a>
                            </li>
                            <li class="swiper-slide projects__item">
                                <a href="" class="projects__item-link">
                                    <img class="projects__item-img" src="img/projects/esad.png " alt="Логотип компании ASAD">
                                </a>
                            </li>
                        </ul>
                    </div>
                    <button class="projects__button-next projects__next"></button>
                </div>
            </div>
        </section>
        <section id="contacts" class="feedback">
            <h2 class="visually-hidden">Заказ обратного звонка</h2>
            <div class="container">
                <div class="feedback__wrapper">
                    <address class="feedback__address">
                            <span class="feedback__rm">Шоурум № 4</span>
                            <span class="feedback__street-address">Леонтьевский переулок, дом 5/1</span>
                        </address>
                    <div class="form-center-wrap">
                        <form class="feedback__form" action="#" method="POST" enctype="multipart/form-data">
                            <label class="feedback__form-label">
                                    <input
                                        type="text"
                                        placeholder="Имя*"
                                        name="Имя"
                                        data-validate-field="name"
                                        aria-label="Введите имя"
                                        class="input-name feedback__form-input"
                                    >
                                </label>
                            <label class="feedback__form-label">
                                    <input
                                        type="tel"
                                        placeholder="Телефон*"
                                        name="Телефон"
                                        data-validate-field="tel"
                                        aria-label="Введите номер телефона"
                                        class="input-tel feedback__form-input"
                                    >
                                </label>
                            <button class="feedback__btn btn-reset">
                                    Заказать обратный звонок
                                </button>
                            <button class="feedback__mobile-btn btn-reset">Заказать</button>
                        </form>
                    </div>
                    <div class="feedback__social">
                        <span class="feedback-social-subtitle">Связаться в один клик</span>
                        <ul class="list-reset feedback__social-list">
                            <li class="feedback__social-item">
                                <a href="https://www.whatsapp.com" target="_blank" class="feedback__social-link">
                                    <svg aria-label="Связатся с нами в Ватсап" class="feedback__social-icon" width="40" height="40" viewbox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <g clip-path="url(#clip0_191243_648)">
                                                <path d="M20 39.375C30.7005 39.375 39.375 30.7005 39.375 20C39.375 9.29948 30.7005 0.625 20 0.625C9.29948 0.625 0.625 9.29948 0.625 20C0.625 30.7005 9.29948 39.375 20 39.375Z" fill="#30BF39"/>
                                                <path d="M25.875 21.751C25.625 21.626 24.3125 20.876 24.0625 20.8135C23.8125 20.6885 23.625 20.6885 23.4375 20.9385C23.25 21.1885 22.6875 21.8135 22.5625 21.9385C22.375 22.126 22.25 22.126 22 22.001C21.75 21.876 20.875 21.5635 19.875 20.5635C19.125 19.8135 18.5625 18.9385 18.4375 18.626C18.3125 18.376 18.4375 18.1885 18.5625 18.0635C18.6875 17.9385 18.8125 17.751 19 17.626C19.1875 17.501 19.1875 17.376 19.3125 17.1885C19.4375 17.001 19.375 16.876 19.3125 16.6885C19.25 16.501 18.75 15.1885 18.5625 14.626C18.375 14.0635 18.125 14.1885 18 14.126C17.8125 14.126 17.6875 14.0635 17.5 14.0635C17.25 14.0635 16.9375 14.1885 16.75 14.376C16.5 14.626 15.75 15.251 15.75 16.5635C15.75 17.876 16.625 19.251 16.75 19.376C16.875 19.5635 18.5 22.4385 21.1875 23.626C23.875 24.8135 23.875 24.4385 24.375 24.4385C24.875 24.4385 26 23.8135 26.25 23.251C26.5 22.626 26.5 22.0635 26.4375 22.001C26.3125 22.001 26.125 21.9385 25.875 21.751ZM20.875 28.1885C19.125 28.1885 17.5 27.6885 16.0625 26.751L12.6875 27.8135L13.8125 24.5635C12.75 23.0635 12.125 21.251 12.125 19.376C12.125 14.501 16.0625 10.5635 20.9375 10.5635C25.8125 10.5635 29.6875 14.501 29.6875 19.376C29.6875 24.251 25.75 28.1885 20.875 28.1885ZM20.875 8.81348C15.0625 8.81348 10.3125 13.5635 10.3125 19.376C10.3125 21.3135 10.8125 23.1885 11.8125 24.8135L9.875 30.501L15.75 28.626C17.3125 29.501 19.0625 29.9385 20.875 29.9385C26.6875 29.9385 31.4375 25.1885 31.4375 19.376C31.4375 13.5635 26.75 8.81348 20.875 8.81348Z" fill="white"/>
                                            </g>
                                            <defs>
                                                <clippath id="clip0_191243_648">
                                                    <rect width="40" height="40" fill="white"/>
                                                </clippath>
                                            </defs>
                                        </svg>
                                </a>
                            </li>
                            <li class="feedback__social-item">
                                <a href="https://telegram.org" target="_blank" class="feedback__social-link">
                                    <svg aria-label="Связатся с нами в Телеграмм" class="feedback__social-icon" width="40" height="40" viewbox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <g clip-path="url(#clip0_191243_651)">
                                                <path d="M20 40C31.0457 40 40 31.0457 40 20C40 8.95431 31.0457 0 20 0C8.95431 0 0 8.95431 0 20C0 31.0457 8.95431 40 20 40Z" fill="#26A5E4"/>
                                                <path
                                                    fill-rule="evenodd"
                                                    clip-rule="evenodd"
                                                    d="M9.05321 19.7889L20.7168 14.7649C26.2711 12.4547 27.4251 12.0534 28.1774 12.0402C28.3429 12.0373 28.7128 12.0783 28.9524 12.2727C29.1548 12.4369 29.2104 12.6587 29.2371 12.8143C29.2637 12.9699 29.2969 13.3246 29.2705 13.6017C28.9695 16.7641 27.6671 24.4386 27.0046 27.9806C26.7242 29.4794 26.1726 29.9819 25.6378 30.0311C24.4763 30.138 23.5944 29.2635 22.4694 28.5261L18.0061 25.528C16.0314 24.2268 17.3115 23.5116 18.4369 22.3428C18.7314 22.0368 23.8487 17.3823 23.9477 16.96C23.9597 16.9072 23.9716 16.7104 23.8547 16.6064C23.7377 16.5024 23.565 16.5384 23.4405 16.5663C23.264 16.6064 20.452 18.465 15.0044 22.1423C14.2062 22.6904 13.4832 22.9575 12.8355 22.9435C12.1214 22.9281 10.7478 22.5397 9.72661 22.2078C8.47408 21.8007 7.4786 21.5854 7.56532 20.8939C7.61044 20.5338 8.1064 20.1655 9.05317 19.789L9.05321 19.7889Z"
                                                    fill="white"
                                                />
                                            </g>
                                            <defs>
                                                <clippath id="clip0_191243_651">
                                                    <rect width="40" height="40" fill="white"/>
                                                </clippath>
                                            </defs>
                                        </svg>
                                </a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>
        <section class="map">
            <h2 class="visually-hidden">Карта</h2>
            <div class="map-moscow" id="map"></div>
        </section>
    </main>
    <footer class="footer">
        <div class="container footer__container">
            <a class="footer__logo">
                <picture>
                    <source srcset="img/header-logo-320.svg" media="(max-width:474px)">
                    <source srcset="img/header-logo-768.svg" media="(max-width:992px)">
                    <source srcset="img/header-logo-1024.svg" media="(max-width:1024px)">
                    <img class="img-logo" src="img/header-logo.svg" alt="Логотип Blanchard Художественная галерея">
                </picture>
            </a>
            <ul class="list-reset footer__list">
                <li class="footer__item">
                    <a href="https://vk.com" target="_blank" class="footer__social-link">
                        <svg aria-label="Страница Вконтакте" class="footer__social-icon" width="45" height="45" viewbox="0 0 45 45" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path d="M22.5 0C10.074 0 0 10.0736 0 22.5C0 34.9264 10.074 45 22.5 45C34.926 45 45 34.9264 45 22.5C45 10.0736 34.926 0 22.5 0ZM33.9132 24.9335C34.9619 25.9577 36.0714 26.9217 37.0128 28.0519C37.4299 28.5519 37.823 29.0688 38.1222 29.6503C38.5495 30.4794 38.1637 31.3886 37.4216 31.4379L32.812 31.4369C31.6215 31.5354 30.6741 31.0553 29.8754 30.2414C29.2378 29.5927 28.6462 28.8999 28.0321 28.2292C27.7812 27.9539 27.517 27.6947 27.2021 27.4907C26.5737 27.0819 26.0277 27.2072 25.6677 27.8636C25.3008 28.5316 25.217 29.2719 25.182 30.0153C25.1319 31.1022 24.8041 31.3863 23.7135 31.4374C21.3832 31.5465 19.1721 31.1929 17.117 30.0181C15.3041 28.9818 13.901 27.5193 12.6783 25.8634C10.2973 22.6353 8.47381 19.0924 6.8354 15.4478C6.46665 14.627 6.73642 14.1878 7.64194 14.1707C9.14639 14.1417 10.6508 14.1454 12.1553 14.1694C12.7676 14.179 13.1727 14.5294 13.4079 15.1071C14.2209 17.1074 15.2176 19.0105 16.4665 20.7755C16.7994 21.2455 17.1391 21.7142 17.623 22.0461C18.157 22.4125 18.5639 22.2915 18.8158 21.6953C18.9769 21.3164 19.0464 20.9113 19.0814 20.5053C19.2011 19.1145 19.2153 17.7242 19.0082 16.339C18.8793 15.4722 18.3918 14.9124 17.5277 14.7485C17.0876 14.6652 17.152 14.5022 17.3661 14.2508C17.7376 13.8163 18.0856 13.5474 18.7812 13.5474L23.9893 13.5465C24.8101 13.7076 24.9942 14.0759 25.1056 14.9027L25.1102 20.6903C25.1006 21.0103 25.2709 21.9586 25.8454 22.1681C26.3058 22.32 26.6096 21.9508 26.8849 21.6594C28.1339 20.334 29.0237 18.7697 29.8206 17.1506C30.1723 16.4366 30.4757 15.6978 30.7703 14.9575C30.9895 14.4101 31.3301 14.1408 31.9479 14.15L36.9631 14.156C37.1108 14.156 37.2609 14.1574 37.4073 14.1827C38.2525 14.3273 38.4841 14.6909 38.2226 15.5154C37.811 16.8109 37.0114 17.89 36.2297 18.9718C35.3919 20.1301 34.4983 21.2478 33.6687 22.4111C32.9064 23.4746 32.9667 24.01 33.9132 24.9335Z" fill="currentColor"/>
                            </svg>
                    </a>
                </li>
                <li class="footer__item">
                    <a href="https://ok.ru" target="_blank" class="footer__social-link">
                        <svg aria-label="Страница  Одноклассники" class="footer__social-icon" width="45" height="45" viewbox="0 0 45 45" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path d="M19.279 14.9859C19.279 16.8409 20.7828 18.3449 22.6379 18.3449C24.4929 18.3449 25.9967 16.8409 25.9967 14.9859C25.9967 13.1309 24.4929 11.6271 22.6379 11.6271C20.7828 11.6271 19.279 13.1309 19.279 14.9859Z" fill="currentColor"/>
                                <path
                                    fill-rule="evenodd"
                                    clip-rule="evenodd"
                                    d="M22.5 45C34.9264 45 45 34.9264 45 22.5C45 10.0736 34.9264 0 22.5 0C10.0736 0 0 10.0736 0 22.5C0 34.9264 10.0736 45 22.5 45ZM14.5125 14.9858C14.5125 10.4984 18.1503 6.86047 22.6379 6.86047C27.1254 6.86047 30.7632 10.4984 30.7632 14.9858C30.7632 19.4734 27.1254 23.1115 22.6379 23.1115C18.1503 23.1115 14.5125 19.4734 14.5125 14.9858ZM30.8117 27.291C30.7086 27.3737 28.7593 28.9142 25.5064 29.5769L30.4165 34.4432C31.28 35.3053 31.2811 36.7042 30.419 37.5677C29.5569 38.431 28.1583 38.4324 27.2945 37.5701L22.5276 32.928L18.1979 37.5402C17.7644 37.9899 17.1862 38.216 16.6074 38.216C16.0553 38.216 15.5027 38.0106 15.074 37.5972C14.1956 36.7502 14.1701 35.3516 15.0171 34.4733L19.6777 29.6025C16.3336 28.9555 14.3039 27.3749 14.1993 27.291C13.2475 26.5277 13.0946 25.1372 13.8579 24.1852C14.6212 23.2334 16.0115 23.0805 16.9636 23.8437C16.9837 23.86 19.1067 25.4549 22.5275 25.4572C25.9483 25.4549 28.0273 23.86 28.0474 23.8437C28.9995 23.0805 30.3899 23.2334 31.1531 24.1852C31.9165 25.1372 31.7636 26.5277 30.8117 27.291Z"
                                    fill="currentColor"
                                />
                            </svg>
                    </a>
                </li>
            </ul>
        </div>
    </footer>

    <script src="libs/inputmask.min.js"></script>
    <script src="libs/just-validate.min.js"></script>
    <script src="libs/focus-visible.js"></script>
    <script src="libs/simpleBar.js"></script>
    <script src="libs/choices.min.js"></script>
    <script src="libs/popper.min.js"></script>
    <script src="libs/tippy-bundle.umd.js"></script>
    <script src="https://unpkg.com/accordion-js@3.1.1/dist/accordion.min.js"></script>
    <script src="libs/swiper-bundle.min.js"></script>
    <script src="https://api-maps.yandex.ru/2.1/?e19e074e-c886-4cf8-9c20-ef3ddd518b21&lang=ru_RU"></script>
    <script src="js/script.js"></script>
</body>

</html>
