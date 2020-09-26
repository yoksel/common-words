# Слова, часто используемые в CSS-классах

## Изображения

`image`, `img`, `picture`, `pic` — картинка

`icon` — иконка

`logo` — логотип

`userpic`, `avatar` — юзерпик, маленькая картинка пользователя

`thumbnail`, `thumb` — миниатюра, уменьшенное изображение

## Текст

`title`, `subject`, `heading`, `headline`, `caption` — заголовок

`subtitle` — подзаголовок

`slogan` — слоган

`lead`, `tagline` — лид-абзац в тексте

`text` — текстовый контент

`desc` — описание, вариант текстового контента

`excerpt` — отрывок текста, обычно используется перед ссылкой «Читать далее...»

`quote`, `blockquote` — цитата

`snippet` — пример кода

`link` — ссылка

`copyright`, `copy` — копирайт

## Списки

`list`, `items` — список

`item` — элемент списка

## Блоки

`page` — корневой элемент страницы

`header` — шапка (страницы или элемента)

`footer` — подвал (страницы или элемента)

`section` — раздел контента (один из нескольких)

`main`, `body` — основная часть (страницы или элемента)

`content` — содержимое элемента

`sidebar` — боковая колонка (страницы или элемента)

`aside` — блок с дополнительной информацией

`widget` — виджет, например, в боковой колонке

## Раскладка

`wrapper`, `wrap` — обёртка, обычно внешняя

`inner` — внутренняя обёртка

`container`, `holder`, `box` — контейнер

`grid` — раскладка (страницы или элемента) в виде сетки (обычно содержит в себе `row` и `col`)

`row` — контейнер в виде строки

`col`, `column` — контейнер в виде столбца

## Элементы управления

`button`, `btn` —  кнопка, например, для отправки формы

`control` — элемент управления, например, стрелки «Вперёд/назад» в фотогалерее, кнопки управления слайдером

`dropdown` — выпадающий список

## Медиавыражения

`phone`, `mobile` — мобильные устройства

`phablet` — телефоны с большим экраном (6-7")

`tablet` — планшеты

`notebook`, `laptop` — ноутбуки

`desktop` — настольные компьютеры

## Размеры

`tiny` — маленький, крохотный

`small` — небольшой

`medium` — средний

`big`, `large` — большой

`huge` — огромный

`narrow` — узкий

`wide` — широкий

## Разное

`search` — поиск

`socials` — блок иконок соцсетей

`advertisement`, `adv`, `commercial`, `promo` — рекламный блок (режутся Адблоком, не рекомендуется использовать такие классы для блоков с внутренней рекламой)

`features`, `benefits` — список основных особенностей товара, услуги

`slider`, `carousel` — слайдер, интерактивный элемент с прокруткой содержимого

`pagination` — постраничная навигация

`user`, `author` — пользователь, автор записи или комментария

`meta` — блок с дополнительной информацией, например, блок тегов и даты в посте

`cart`, `basket` — корзина

`breadcrumbs` — навигационная цепочка, «хлебные крошки»

`more`, `all` — ссылка на полную информацию

`modal` — модальное (диалоговое) окно

`popup` — всплывающее окно

`tooltip`, `tip` — всплывающее подсказки

`preview` — анонс, отрывок, например новости или поста, может состоять из заголовка, описания и картинки. Предполагается ссылка на полную версию

`overlay` — перекрывающий слой, например, для затемнения изображений или создания модальных окон

## Состояния

`active`, `current` — активный элемент, например, текущий пункт меню

`visible` — видимый элемент

`hidden` — скрытый элемент

`error` — статус ошибки

`warning` — статус предупреждения

`success` — статус успешного выполнения задачи

`pending` — состояние ожидания, например, перед сменой статуса на error или success

## Примеры использования

### Простой список

```html
<ul class="list">
  <li class="item">Первое</li>
  <li class="item">Второе</li>
  <li class="item">Третье</li>
</ul>
```

### Картинка пользователя (юзерпик)

```html
<div class="user">
  <img class="user__img" src="userpic.png" alt="Дормидонт Петрович">
  <a class="user__link" href="#">Дормидонт Петрович</a>
</div>
```

### Галерея

```html
<div class="gallery">
  <ul class="gallery__list">
    <li class="gallery__item">
      <img class="gallery__img" src="flowers.jpg" alt="Цветём как в последний раз">
    </li>
    <li class="gallery__item">
      <img class="gallery__img" src="trees.jpg" alt="Парк «Три сосны»">
    </li>
  </ul>
</div>
```

### Навигация

```html
<nav class="nav">
  <a class="nav__link nav__link--active">Главная</a>
  <a class="nav__link" href="#">Второстепенная</a>
  <a class="nav__link" href="#">Третья с конца</a>
  <a class="nav__link" href="#">Предпоследняя</a>
  <a class="nav__link" href="#">Совсем конец</a>
</nav>
```

```html
<nav class="nav">
  <ul class="nav__list">
    <li class="nav__item nav__item--current">
      <a class="nav__link">Главная</a>
    </li>
    <li class="nav__item">
      <a class="nav__link" href="#">Статьи</a>
    </li>
    <li class="nav__item">
      <a class="nav__link" href="#">Фотогалерея</a>
    </li>
    <li class="nav__item">
      <a class="nav__link" href="#">Контакты</a>
    </li>
  </ul>
</nav>
```

### Виджет в боковой колонке

```html
<div class="widget">
  <h4 class="widget__title">Выращиваем желе</h4>

  <div class="widget__content">
    <p>Чтобы вырастить общительное дружелюбное желе,
    нам потребуется рулон поролона, два килограмма сахара,
    три яйца и пол чайной чашки ацетона.</p>

    <a class="widget__link" href="#">Не читать дальше...</a>
  </div>
</div>
```

### Блок новостей

```html
<div class="news">
    <h3 class="news__title">Вчерашние новости</h3>

    <ul class="news__list">
        <!-- к классу элемента добавляем класс блока,
             чтобы создать новое пространство имён -->
        <li class="news__item item-news">
            <h4 class="item-news__title">Соревнования среди воблы по конькобежному спорту</h4>
            <div class="item-news__text">
              <p>Победила команда килек из Петрозаводска</p>

              <a href="#" class="item-news__link">Читать дальше</a>
            </div>
        </li>

        <li class="news__item item-news">
            <h4 class="item-news__title">Учёные уточнили роль напильника в уходе за ногтями</h4>
            <div class="item-news__text">
              <p>Британские учёные высоко оценили вклад
                напильника в отращивание полутораметровых ногтей.</p>

              <a href="#" class="item-news__link">Не читать дальше</a>
            </div>
        </li>
    </ul>
</div>
```

### Статья или пост в блоге (простой вариант)

```html
<article class="article">
  <h3 class="article__title">Нащупываем чакры у пучка петрушки</h3>
  <time class="article__datetime">32 мая, 10:87</time>

  <div class="article__author author-article">
    <img class="author-article__img" src="userpic.png" alt="Клешня Андреевна">
    <a class="author-article__link" href="#">Клешня Андреевна Долгорукая</a>
    <div class="author-article__desc">Наш эксперт по чакрам</div>
  </div>

  <div class="article__content">
    Сходите на рынок и купите у старушек пучок петрушки грамм на 100.
    Как следует переберите, очистите от жуков и гусениц. Жуков отдайте поиграться
    коту, гусениц поселите в горшок с кактусами, пусть одна будет Джоном,
    вторая Билли, а у вас в горшке теперь будет Дикий Запад. Вернитесь
    к пучку петрушки. Ласково взгляните на него и как следует почешите
    за ухом, можно себе или коту. Перевяжите атласной ленточкой,
    непременно завяжите бант. Поздравляем! Теперь у вас есть полностью
    одомашненный пучок петрушки, который будет весело бегать за вами
    по пятам и проращивать свои семена в ваших тапках.
  </div>
</article>
```

### Статья или пост в блоге (сложный вариант)

```html
<article class="entry">
  <header class="entry__header">
    <h3 class="entry__title title-entry">
      <a class="title-entry__link" href="#">Резиновые уточки как способ самопознания</a>
    </h3>

    <time class="entry__datetime">32 мая, 10:87</time>
  </header>

  <div class="entry__author author-entry">
    <img class="author-entry__img" src="userpic.png" alt="Василиса Сергеевич">

    <a class="author-entry__link" href="#">Василиса Сергеевич</a>
  </div>

  <div class="entry__content">
    Достаньте с чердака коробку с полусотней резиновых уточек,
    оставшихся после празднования нового года. Из уточек
    и горящих свечей выложите пентаграмму на полу комнаты.
    Сядьте посередине в позу лотоса, в каждую руку возьмите
    по немецко-бразильскому словарю, прокашляйтесь, наберите
    полную грудь воздуха и громко и уверенно,
    с полной самоотдачей скажите "Кря!"
  </div>

  <div class="entry__tags tags-entry">
    <h4 class="tags-entry__title">Метки</h4>

    <ul class="tags-entry__list">
      <li class="tags-entry__item">
        <a class="tags-entry__link" href="#">хоровод своими руками</a>
      </li>
      <li class="tags-entry__item">
        <a class="tags-entry__link" href="#">фарфоровые тапки</a>
      </li>
      <li class="tags-entry__item">
        <a class="tags-entry__link" href="#">гуталин в кулинарии</a>
      </li>
    </ul>
  </div>

  <div class="entry__actions actions-entry">
    <ul class="actions-entry__list">
      <li class="actions-entry__item actions-entry__item--read">
        <a class="actions-entry__link" href="#">238 ответов</a>
      </li>
      <li class="actions-entry__item actions-entry__item--write">
        <a class="actions-entry__link" href="#">Написать в спортлото</a>
      </li>
      <li class="actions-entry__item actions-entry__item--share">
        <a class="actions-entry__link" href="#">Поделиться</a>
      </li>
    </ul>
  </div>
</article>
```
