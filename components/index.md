---
layout: with-sidebar
title: 'Components'
---

## Overview

Putting it all together.

In this section, we will document common UI elements, such as buttons, links, tags, horizontal rules, lists, tables... Each component displays an embedded Figma component (for designing and mocking up) as well as a Codepen snippet to show the HTML markup and associated CSS styles.

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
