# Слова, часто используемые в CSS-классах

## Изображения

`img` — картинка

`icon` — иконка

`logo` — логотип

`userpic` — юзерпик, маленькая картинка пользователя

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


## Примеры кода


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
