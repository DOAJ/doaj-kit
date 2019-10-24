---
layout: with-sidebar
title: 'Typography'
---

## Typeface pairing

Two matching typefaces, based on their x-height, were selected to create a combination of serifs and sans-serifs. We will not load all of the weights, styles, and scripts at first to avoid performance issues.

Their use is restricted to the following:  

{% include blocks/pairing.html %}

- [_Spectral_](https://design.google/library/spectral-new-screen-first-typeface/), [_Source Sans Pro_](https://typographica.org/typeface-reviews/source-sans/) & [_Source Code Pro_](https://adobe-fonts.github.io/source-code-pro/) are all “workhorse” typefaces
  - They have a very flexible usage as well as a large range of weights, widths and styles (italics, light to regular to semibold to bold to black).
  - All were designed for screen reading, UI design, and generally better legibility.
- All the fonts are free & SIL-licensed open source
  - If any updates are made (e.g. new script support), we can get them at no extra cost.
- On _Spectral_: “While deeply rooted in French type design history, Spectral tends to reject the idea of any country-specific flavor—much in the same way that Elzevir typefaces have always represented a cross-current of western influences from Italy, France, the Netherlands, Germany, and the United States. From fifteenth-century France to sixteenth-century Holland and back to nineteenth-century France, the underlying concept of these Elzevir typefaces still makes sense in 2017. (…)  While developing Spectral, we looked back to the Elzevir typefaces for guidance because their genius, as a cultural form, was to implicitly acknowledge that the nature of information had changed. No longer privileged, information had become popular, compact, portable, eminently transmissible, and reproducible.”  
- On _Source Sans Pro_: “The typeface is inspired by the forms of the American Type Founders' gothics by Morris Fuller Benton, such as News Gothic, Lightline Gothic and Franklin Gothic, modified with both a larger x-height and character width and more humanist-influenced italic forms.”
- Besides Latin & Latin extended scripts,
  - **Spectral** supports Vietnamese & Cyrillic (146 languages, 1,221 glyphs);
  - **Source Sans Pro** supports Cyrillic, Cyrillic Extended, Greek, & Greek Extended (103 languages, 857 glyphs);
  - **Source Code Pro** supports Cyrillic, Cyrillic Extended, Greek, & Vietnamese.
- Other unsupported scripts, such as Arabic or Indian scripts like Devanagari, will be displayed with the user’s default system font.

---

## Typographic scale

To create harmony in our font usage, we are using a typescale in minor third for headings (`<h1>`...`<h6>`) and body text (any flow content such as paragraphs and lists), with a base `font-size` of `16px`.

{% include blocks/headings.html %}
