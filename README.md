# Слова, часто используемые в CSS-классах

## Изображения

`img` — картинка

`icon` — иконка

`logo` — логотип

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

## Разное

`button`, `btn` —  кнопка

`user`, `author` — пользователь, автор записи или комментария


## Пример кода

```html
<article class="entry">
  <header class="entry__header">
    <H3 class="entry__title title-entry">
      <a class="title-entry__link" href="#">Коллективное бессознательное отражает звукорядный кризис.</a>
    </H3>
    <time class="title-entry__datetime">32 мая, 10:87</time>
  </header>

  <div class="entry__author autor-entry">
    <img class="autor-entry__img" src="userpic.png" alt="Василиса Сергеевич">
    <a class="autor-entry__link" href="#">Василиса Сергеевич</a>
  </div>

  <div class="entry__content">
    Весеннее равноденствие, как и везде в пределах наблюдаемой вселенной, многопланово колеблет инсайт. В связи с этим нужно подчеркнуть, что фаза вероятна.
  </div>

  <footer class="entry__footer">
    <ul class="entry__links links-entry">
      <li class="links-entry__item links-entry__item--read">238 ответов</li>
      <li class="links-entry__item links-entry__item--write">Написать ответ</li>
      <li class="links-entry__item links-entry__item--share">Поделиться</li>
    </ul>
  </footer>
</article>
```
