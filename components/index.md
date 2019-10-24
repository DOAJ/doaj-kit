---
layout: with-sidebar
title: 'Components'
---

### Overview

Putting it all together.

Examples of common UI elements, such as buttons, lists of links, tags, horizontal rules, and links within headings (styled as superscript).

---

### Stylesheet structure

Using a CSS pre-processor will help us sustainably organise our stylesheets and facilitate updates with the use of variables and mixins. Coupled with the BEM methodology for naming components, we recommend the following SCSS or LESS architecture in order to keep our stylesheet light and simple.

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
