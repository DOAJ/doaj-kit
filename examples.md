---
layout: with-sidebar
title: 'Implementation examples'
---

### Grid: ⅓ + ⅔ of the page (two columns), no sidebar

The examples here show one semantically-grouped section that includes a heading (“Abstract”) and its corresponding paragraph using the following markup (semantic markup is highlighted):

```html
<section class="row">
  <div class="col-1">
    <h3>[title…]</h3>
  </div>
  <div class="col-2">
    <p>[text…]</p>
  </div>
</section>
```

#### Mobile

#### Tablet

#### Desktop

---

### Grid: ⅓ + ⅓ + ⅓ of the page (three columns), no sidebar

#### Mobile

#### Tablet

#### Desktop

---

### Article details page

Testing the style guide on an [article](https://doaj.org/article/10f222e2075a4d9c83478d64e03e1210), without the header and footer. Shows `<h1>`, `<h2>`, `<h3>`, `<p>`, `<a>`, `<em>` or `<i>`, `<hr>`, `<dl>`, `<dt>`, `<dd>`, and `<small>`.

![Example of an article detail page](../img/implementation/article.png)

---

### Dark mode

The default theme is a light one (white background). When mobile users request the system to use a dark colour theme, detected by the CSS media query `prefers-color-scheme`, the site’s warm white are swapped to warm black; the accent colours’ darker shades are swapped to their lighter tones.

The colours remain accessible, thanks to a flexible palette. Desktop users wishing to use dark mode can do so with the click of a button.

![Example of dark mode](../img/implementation/darkmode.png)
