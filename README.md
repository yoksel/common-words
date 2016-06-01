# Слова, часто используемые в CSS-классах

## Изображения

`img` — картинка

`icon` — иконка

`logo` — логотип

`userpic`, `avatar` — юзерпик, маленькая картинка пользователя

## Текст

`title` — заголовок

`text` — текстовый контент

`desc` — описание, вариант текстового контента

`link` — ссылка

## Списки

`list`, `items` — список

`item` — элемент списка

## Раскладка

`wrapper` — обёртка

`container` — контейнер

`inner` — внутренний элемент

`header` — шапка (страницы или элемента)

`footer` — подвал (страницы или элемента)

`content` — содержимое элемента

`widget` — виджет, например, в боковой колонке

## Элементы управления

`button`, `btn` —  кнопка, например для отправки формы

`control` — элемент управления, например, стрелки "Вперёд/назад" в фотогалерее, кнопки управления слайдером

## Разное

`user`, `author` — пользователь, автор записи или комментария

`socials` — блок иконок соцсетей

`active`, `current` — активный элемент, например, текущий пункт меню


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
<div class="gallery gallery--slider">
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
  <a class="nav__link" href="#">Статьи</a>
  <a class="nav__link" href="#">Фотогалерея</a>
  <a class="nav__link" href="#">Контакты</a>
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
  <h4 class="widget__tilte">Выращиваем желе</h4>

  <div class="widget__content">
    Гармоническое микророндо, в первом приближении, заканчивает винил, но если бы песен было раз в пять меньше, было бы лучше для всех. 
  </div>
</div>
```

### Статья

```html
<article class="article">
  <h3 class="article__title">
    Нащупываем чакры у пучка петрушки
  </h3>
  <time class="article__datetime">32 мая, 10:87</time>
  
  <div class="article__author author-article">
    <img class="author-article__img" src="userpic.png" alt="Клешня Андреевна">
    <a class="author-article__link" href="#">Клешня Андреевна Долгорукая</a>
    <div class="author-article__desc">эксперт по чакрам</div>
  </div>

  <div class="article__content">
    Бихевиоризм, несмотря на внешние воздействия, субстратно иллюстрирует жидкофазный ионный хвост.
  </div>
</article>
```

### Пост в ленте постов

```html
<article class="entry">
  <header class="entry__header">
    <h3 class="entry__title title-entry">
      <a class="title-entry__link" href="#">Резиновые уточки как способ самопознания</a>
    </h3>
    <time class="title-entry__datetime">32 мая, 10:87</time>
  </header>

  <div class="entry__author author-entry">
    <img class="author-entry__img" src="userpic.png" alt="Василиса Сергеевич">
    <a class="author-entry__link" href="#">Василиса Сергеевич</a>
  </div>

  <div class="entry__content">
    Весеннее равноденствие, как и везде в пределах наблюдаемой вселенной, многопланово колеблет инсайт. В связи с этим нужно подчеркнуть, что фаза вероятна.
  </div>
  
  <div class="entry__tags tags-entry">
    <h4 class="tags-entry__tilte">Метки</h4>
    
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

  <menu class="entry__menu menu-entry">
    <ul class="menu-entry__list">
      <li class="menu-entry__item menu-entry__item--read">
        <a class="menu-entry__link" href="#">238 ответов</a>
      </li>
      <li class="menu-entry__item menu-entry__item--write">
        <a class="menu-entry__link" href="#">Написать ответ</a>
      </li>
      <li class="menu-entry__item menu-entry__item--share">
        <a class="menu-entry__link" href="#">Поделиться</a>
      </li>
    </ul>
  </menu>
</article>
```
