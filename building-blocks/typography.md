---
layout: with-sidebar
title: 'Typography'
category: building-block
---

We have paired the SIL-licensed open source typefaces _Spectral_, a serif, _Source Sans Pro_, a sans-serif, and _Source Code Pro_, a monospaced sans-serif, to be used throughout DOAJ’s interface. All fonts were designed with screen reading and user interfaces in mind. 

Their usage is restricted to the following:  

{% include blocks/pairing.html %}

- Besides Latin & Latin extended scripts,
  - **Spectral** supports Vietnamese & Cyrillic (146 languages, 1,221 glyphs);
  - **Source Sans Pro** supports Cyrillic, Cyrillic Extended, Greek, & Greek Extended (103 languages, 857 glyphs);
  - **Source Code Pro** supports Cyrillic, Cyrillic Extended, Greek, & Vietnamese.
- Other unsupported scripts, such as Arabic or Indian scripts like Devanagari, will be displayed with the user’s default system font.

---

## Typographic scale

To create harmony in our font usage, we are using a typescale in minor third for headings (`<h1>`...`<h6>`) and body text (any flow content such as paragraphs and lists), with a base `font-size` of `16px`.

{% include blocks/headings.html %}
