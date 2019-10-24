---
layout: with-sidebar
title: 'Layout'
category: building-block
---

Instead of using Bootstrap’s 12-column grid, we simplified the layout’s grid to be based on only three columns. All content (text, images) must be left-aligned (no justified or centred text). There are a total of six different variations.

This restricts the possible page layouts so that it doesn’t allow for too many variations in order to create consistency across different pages, regardless of the user’s viewport size. It should remain modular enough to accommodate new types of content while allowing a comfortable reading experience.  

We offer two types of page layouts: with a side navigation on the left, or without. If we find that these choices are too restrictive, we can easily update it (e.g. use six columns instead of three).

**Without** a sidebar allows for four different types of content blocks using thirds or two-thirds of the page.

![Grid without sidebar]({{ baseurl }}/img/blocks/No sidebar.png)

We won’t allow a full-width content block to avoid long lines of text, which hinders the proper parsing of longer paragraphs.

**With a sidebar** allows for two different types of content blocks using full-width (two-thirds) and halves (thirds) of the remaining space.

![Grid with a sidebar]({{ baseurl }}/img/blocks/With sidebar.png)

The sidebar area (in red) should be mainly used for in-page navigation. It takes up the whole width of the page on smaller viewports (e.g. mobile devices). Examples of uses of the sidebar include:
- a list of filters for the search tool;
- a table of contents for an information page that has many sections, like the FAQs;
- some sort of promotion space (upcoming events, partnerships);
- a Twitter or news feed.

This layout is meant to encourage the use of white space and to allow for the text and images to breathe.
