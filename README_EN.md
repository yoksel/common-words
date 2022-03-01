
# Words commonly used in CSS classes

## Images

`image`, `img`, `picture`, `pic` - picture

`icon` — icon

`logo` — logo

`userpic`, `avatar` — userpic, a small picture of the user

`thumbnail`, `thumb` — thumbnail, thumbnail

## Text

`title`, `subject`, `heading`, `headline`, `caption` — title

`subtitle` — subtitle

`slogan` — slogan

`lead`, `tagline` — lead paragraph in the text

`text` - text content

`desc` — description, text content option

`excerpt` - excerpt of text, usually used before the "Read more..." link

`quote`, `blockquote` — quote

`snippet` - sample code

`link` — link

`copyright`, `copy` - copyright

## Lists

`list`, `items` - list

`item` - list item

## Blocks

`page` is the root element of the page

`header` - header (page or element)

`footer` - footer (of a page or element)

`section` - content section (one of several)

`main`, `body` - the main part (of the page or element)

`content` - element content

`sidebar` - sidebar (of a page or element)

`aside` - block with additional information

`widget` - a widget, for example, in a sidebar

## Layout

`wrapper`, `wrap` - wrapper, usually outer

`inner` - inner wrapper

`container`, `holder`, `box` — container

`grid` - layout (page or element) in the form of a grid (usually contains `row` and `col`)

`row` - string container

`col`, `column` - column container

## Controls

`button`, `btn` — button, e.g. for submitting a form

`control` - a control element, for example, forward / backward arrows in a photo gallery, slider control buttons

`dropdown` - dropdown list

## media expressions

`phone`, `mobile` — mobile devices

`phablet` - large screen phones (6-7")

`table` — tablets

`notebook`, `laptop` — laptops

`desktop` - desktop computers

## Dimensions

`tiny` - small, tiny

`small`

`medium`

`big`, `large`

`huge` - huge

`narrow` - narrow

`wide` - wide

## Miscellaneous

`search` - search

`socials` — block of social media icons

`advertisement`, `adv`, `commercial`, `promo` - ad block (cut by Adblock, it is not recommended to use such classes for blocks with internal ads)

`features`, `benefits` - a list of the main features of the product, service

`slider`, `carousel` — slider, interactive element with content scrolling

`pagination` - pagination

`user`, `author` — user, post or comment author

`meta` - a block with additional information, for example, a block of tags and dates in a post

`cart`, `basket` ​​- basket

`breadcrumbs` - navigation chain, "breadcrumbs"

`more`, `all` — link to complete information

`modal` - modal (dialog) window

`popup` — popup window

`tooltip`, `tip` — tooltips

`preview` - an announcement, an excerpt, such as news or a post, may consist of a title, description and picture. Link to full version expected

`overlay` - an overlay layer, for example, to darken images or create modal windows

## States

`active`, `current` - active element, for example, the current menu item

`visible` — visible element

`hidden` - hidden element

`error` — error status

`warning` — warning status

`success` — status of successful completion of the task

`pending` - waiting state, for example, before changing the status to error or success

## Examples of using

### Simple list

```html
<ul class =" list " > 
  <li class =" item " > First </ li> 
  <li class =" item " > Second </ li> 
  <li class =" item " > Third </ li> 
</ ul >
```

### User picture (userpic)

```html
<div class="user">
  <img class="user__img" src="userpic.png" alt="Дормидонт Петрович">
  <a class="user__link" href="#">Дормидонт Петрович</a>
</ div>
```

### Gallery

```html
<div  class =" gallery " > 
  <ul  class =" gallery__list " > 
    <li  class =" gallery__item " > 
      <img  class =" gallery__img " src =" flowers.jpg " alt =" Blooming like the last time " > 
    </ li > 
    <li  class =" gallery_item " > 
      <img  class ="gallery__img " src =" trees.jpg " alt =" Three Pines Park " > < 
    / li > 
  </ ul > 
</ div >
```

### Navigation

```html
<nav  class =" nav " > 
  <a  class =" nav__link nav__link--active " > Main </ a > 
  <a  class =" nav__link " href =" # " > Secondary </ a > 
  <a  class =" nav__link " href =" # " > Third from the end </ a > 
  <class  = "nav__link " href =" # " > Penultimate </ a > 
  <a  class =" nav__link " href =" # " > Quite the end </ a > 
</ nav >
```

```html
<nav  class =" nav " > 
  <ul  class =" nav__list " > 
    <li  class =" nav__item nav__item--current " > 
      <a  class =" nav__link " > Home </ a > 
    </ li > 
    <li  class =" nav__item " > 
      <a  class =" nav__link " href ="# " >Articles </ a > 
    </ li > 
    <li  class =" nav__item " > 
      <a  class =" nav__link " href =" # " > Photo Gallery </ a > 
    </ li > 
    <li  class =" nav__item " > 
      <a  class =" nav_link " href =" # " >Contacts </a> _ _
    </ li > 
  </ ul > 
</ nav >
```

### Widget in sidebar

```html
<div  class =" widget " > 
  <h4  class =" widget_title " > Grow Jelly </ h4 >

  <div  class =" widget__content " > 
    <p > To grow social friendly jelly,
    we need a roll of foam rubber, two kilograms of sugar,
    three eggs and half a tea cup of acetone. </ p >

    <a  class =" widget__link " href =" # " > Read no further... </ a > 
  </ div > 
</ div >
```

### News block

```html
<div  class =" news " > 
    <h3  class =" news__title " > Yesterday's news </ h3 >

    <ul  class =" news__list " > 
        <!-- add a block class to the item class 
             to create a new namespace --> 
        <li  class =" news__item item-news " > 
            <h4  class =" item -news__title " > speed skating wobbles </ h4 > 
            <div  class =" item-news__text " > 
              <p > Kilek team from Petrozavodsk won </ p >

              <a  href =" # " class =" item-news__link " > Read more </ a > 
            </ div > 
        </ li >

        <li  class =" news__item item-news " > 
            <h4  class =" item-news__title " > Scientists have clarified the role of a file in nail care </ h4 > 
            <div  class =" item-news__text " > 
              <p > British scientists highly appreciated contribution
                file in growing one and a half meter nails. </ p >

              <a  href =" # " class =" item-news__link " > Do not read further </ a > 
            </ div > 
        </ li > 
    </ ul > 
</ div >
```

### Article or blog post (simple version)

```html
<article  class =" article " > 
  <h3  class =" article__title " > Feeling for the chakras of a bunch of parsley </ h3 > 
  <time  class = " article__datetime " > May 32, 10:87 </ time >

  <div  class =" article__author author-article " > 
    <img  class =" author-article__img " src =" userpic.png " alt =" Kleshnya Andreevna " > 
    <a  class =" author-article__link " href =" # " > Kleshnya Andreevna Dolgorukaya </ a > 
    <div  class =" author-article__desc " >Our Chakra Expert </ div> 
  </ div >

  <div  class =" article__content " >
    Go to the market and buy a 100 gram bunch of parsley from the old ladies.
    Sort through, clean from beetles and caterpillars. Let the bugs play
    put the cat, caterpillars in a pot of cacti, let one be John,
    the second Billy, and you will now have the Wild West in the pot. Come back
    to a bunch of parsley. Look at him affectionately and scratch him properly
    behind the ear, you can yourself or a cat. Tie with satin ribbon
    be sure to tie a bow. Congratulations! Now you have completely
    a domesticated bunch of parsley that will have fun chasing you
    on your heels and germinate your seeds in your slippers.
  </ div > 
</ article >
```

### Article or blog post (hard)

```html
<article  class =" entry " > 
  <header  class =" entry_header " > 
    <h3  class =" entry_title title-entry " > 
      <a  class =" title-entry__link " href =" # " > Rubber ducks as a way of self-discovery </ a > 
    </ h3 >

    <time  class =" entry_datetime " > May 32, 10:87 </ time > 
  </ header >

  <div  class =" entry_author author-entry " > 
    <img  class =" author-entry__img " src =" userpic.png " alt =" Vasilisa Sergeyevich " >

    <a  class =" author-entry__link " href =" # " > Vasilisa Sergeevich </ a > 
  </ div >

  <div  class =" entry__content " >
    Get a box of fifty rubber ducks from the attic,
    remaining after the celebration of the new year. From ducks
    and burning candles lay out a pentagram on the floor of the room.
    Sit in the middle in the lotus position, in each hand take
    according to the German-Brazilian dictionary, cough, dial
    full chest of air and loud and confident,
    with full dedication, say "Quack!"
  </ div >

  <div  class =" entry_tags tags-entry " > 
    <h4  class =" tags-entry__title " > Tags </ h4 >

    <ul  class =" tags-entry__list " > 
      <li  class =" tags-entry__item " > 
        <a  class =" tags-entry__link " href =" # " > diy dance </ a > 
      </ li > 
      <li  class = " tags-entry__item " > 
        <a  class =" tags-entry__link " href ="# " >porcelain slippers </ a > 
      </ li > 
      <li  class =" tags-entry__item " > 
        <a  class =" tags-entry__link " href =" # " > shoe polish in cooking </ a > 
      </ li > 
    </ ul > 
  </ div >

  <div  class =" entry__actions actions-entry " > 
    <ul  class =" actions-entry__list " > 
      <li  class =" actions-entry__item actions-entry__item--read " > 
        <a  class =" actions-entry__link " href =" # " > 238 responses </ a > 
      </ li > 
      <li  class ="actions-entry__item actions-entry__item--write " > 
        <a  class =" actions-entry__link " href =" # " > Write to sportsloto </ a > 
      </ li > 
      <li  class =" actions-entry__item actions-entry__item--share " > 
        <a  class =" actions-entry__link " href =" # " > Share </a> </ li > 
      </ ul > </ div ></ article
    
  
>
```