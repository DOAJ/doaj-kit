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

### Stylesheet structure (WIP)

Using a CSS pre-processor will help us sustainably organise our stylesheets and facilitate updates with the use of variables and mixins. Coupled with the BEM methodology for naming components, we recommend the following SCSS file architecture in order to keep our stylesheet light and simple.

```
sass/
|
|--- _base.scss
|
|--- _grid.scss
|
|--- _palette.scss
|
|--- _typography.scss
|
|--- _sidebar.scss
|
|--- _light-mode.scss
|
`--- _dark-mode.scss
```
