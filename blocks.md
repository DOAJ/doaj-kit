---
layout: with-sidebar
title: 'Building blocks'
---

In general, we recommend a parsimonious use of any of the following assets in order to keep both the markup (HTML) and layout (CSS) as minimal and elementary as possible.

### Colours

The palette plays on a polychromatic selection of hues, with an inclination for warmer colours.

We’ve kept the colour orange, a reminder of PLOS’ Open Access orange and a colour familiar to DOAJ’s user base, but it has matured into a darker burnt orange shade as well as softer light orange tint.

{% include blocks/colours.html %}

- Warm Black,
- Warm Grey, and
- Warm White
  - ...make up our greyscale palette.
- Pine Green and Teal;
- Venetian Red and Crimson;
- Burnt Orange and Orange
  - ...for colour accents.

#### Proportions

Generally, every page on the website should adhere to the following proportions (collaterals like PDF reports may deviate from this, to use full-page blocks of colours for example):

![Colour proportions](../img/blocks/colourproportion.png)

- 80% greyscale:
  - Warm White
  - Warm Grey
  - Warm Black
- 20% colours:
  - Teal & Pine Green
  - Orange & Burnt Orange
  - Crimson & Venetian Red

#### Accessible combinations

Not all colours can be mixed together if we want content to be accessible for users with colour vision deficiencies (CVDs). Graphical and non-essential page elements (i.e. not required to understand the content) are not bound by these combinations.

The following are the acceptable (WCAG AA-compliant) combinations of colours for text and background.

{% include blocks/colour-combos.html %}

#### Themes

Although the palette includes three different hues (orange, crimson, and teal), we recommend using a single hue per page.

Each colour can be associated with three types of pages, depending on their general objective:
1. **Burnt orange**: learning about what we do
   - News
   - FAQs
   - Privacy
   - About…
2. **Venetian red**: submitting an application
   - Apply
   - For Publishers
   - Copyright & Licensing Help…
3. **Pine green**: accessing the content
   - Search
   - Widgets
   - OAI-PMH
   - API…

![Three types of content & corresponding hues](../img/implementation/threehues.png)

---

### Typefaces

Two matching typefaces, based on their x-height, were selected to create a combination of serifs and sans-serifs. We will not load all of the weights, styles, and scripts at first to avoid performance issues.

Their use is restricted to the following:  

![Typeface pairings](../img/blocks/typepairings.png)

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

#### Typographic scale

To create harmony in our font usage, we are using a typescale in minor third for headings (`<h1>`...`<h6>`) and body text (any flow content such as paragraphs and lists), with a base `font-size` of `16px`.

{% include blocks/headings.html %}

---

### Icons

For consistency, the [Feather icon set](https://feathericons.com/) will be the only set of icons used. As with the typefaces, it is a free and open source set of icons that is continually being updated.

It offers an extensive choice of elegant, minimal and understated icons for use on DOAJ’s website and collaterals (PDF, etc.) while covering basic UI actions (close, expand, minimise, ascend, descend).

{% include blocks/icons.html %}

---

### Grid

Instead of using Bootstrap’s 12-column grid, we simplified the grid to be based on only three columns. All content (text, images) must be left-aligned (no justified or centred text). There are a total of six different variations.

This restricts the possible layouts so that it doesn’t allow for too many variations in order to create consistency across different pages, regardless of the user’s viewport size. It should remain modular enough to accommodate new types of content while allowing a comfortable reading experience.  

We offer two types of page layouts: with a side navigation on the left, or without. If we find that these choices are too restrictive, we can easily update it (e.g. use six columns instead of three).

**Without** a sidebar allows for four different types of content blocks using thirds or two-thirds of the page.

![Grid without sidebar](../img/blocks/No sidebar.png)

We won’t allow a full-width content block to avoid long lines of text, which hinders the proper parsing of longer paragraphs.

**With a sidebar** allows for two different types of content blocks using full-width (two-thirds) and halves (thirds) of the remaining space.

![Grid with a sidebar](../img/blocks/With sidebar.png)

The sidebar area (in red) should be mainly used for in-page navigation. It takes up the whole width of the page on smaller viewports (e.g. mobile devices). Examples of uses of the sidebar include:
- a list of filters for the search tool;
- a table of contents for an information page that has many sections, like the FAQs;
- some sort of promotion space (upcoming events, partnerships);
- a Twitter or news feed.

This layout is meant to encourage the use of white space and to allow for the text and images to breathe.

---

###
