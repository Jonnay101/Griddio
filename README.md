# Griddio

Griddio is yet another simple, responsive css grid system! It's a small project i started in an attempt to learn more about css grids while learning a bit more about Sass. I also wanted to make a grid where I could choose how many columns I could have per page.

### Just add the Griddio classes to your html...

#### First you must add a wrapper to contain all your content...
```html
<div class="wrapper"></div>;
```

#### Then you must add a row to contain your columns...

```html
<div class="row"></div>;
```

#### Inside there you can add your columns...

First the screen size at which the columns will work...

- **xsc:** eXtra Small Column
- **sc:** Small Column
- **mc:** Medium Column
- **lc:** Large Column

Follwed by a dash(-), then the number of columns you would like the element to take up, eg...

```html
<div class="sc-8 lc-4"></div>;
```

*The above example will give this div element a width of 8 columns on small screens and 4 columns on large screens. This is shown in greater detail in the suplied griddio.html file.*

#### The whole hierarchy...

```html
<div class="wrapper">
  <div class="row">
    <div class="sc-8 lc-4"></div>
  </div>
</div>
```

#### Just link to the griddio.css file in the head of your css and your on your way.

```html
<link type="text/css" rel="stylesheet" href="css/griddio.css">
```

This project is not currently tested on multiple browsers. I've also included the sass files so please feel free to mess with it and improve it!!!
