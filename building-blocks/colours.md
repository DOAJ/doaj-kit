---
layout: with-sidebar
title: 'Colours'
category: building-block
---

In order to remain consistent in our user interfaces and to help achieve a better user experience, we have set guidelines on colour usage for DOAJ.org as we as all DOAJ-related digital platforms and print media. We are continuing to improve on better guidance regarding meaningful colour usage.

No colours used on any DOAJ page should deviate from this palette.

If using our SCSS stylesheets, as on the website, make sure to use the variable (e.g. `$grapefruit`) exclusively, and never the HSL or HEX codes.

<iframe title="Colour palette on Figma" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FCLkv5unlaRSU5YABUNqN1v%2FBuilding-blocks%3Fnode-id%3D42%253A45" allowfullscreen></iframe>

| Name                                                                        | HSL (preferred)       | HEX       |
|-----------------------------------------------------------------------------|-----------------------|-----------|
| **Greyscale**                                                                                                   |
| <span data-feather="droplet" class="white-fill"></span> `$white`            | `hsl(0, 0%, 100%)`    | `#FFFFFF` |
| <span data-feather="droplet" class="light-grey-fill"></span> `$light-grey`  | `hsl(0, 10%, 96%)`    | `#F6F4F4` |
| <span data-feather="droplet" class="dark-grey-fill"></span> `$dark-grey`    | `hsl(30, 3%, 35%)`    | `#5C5956` |
| <span data-feather="droplet" class="black-fill"></span> `$warm-black`       | `hsl(30, 5%, 15%)`    | `#282624` |
| **Primary colours**                                                                                             |
| <span data-feather="droplet" class="sanguine-fill"></span> `$sanguine`      | `hsl(15, 88%, 32%)`   | `#982E0A` |
| <span data-feather="droplet" class="grapefruit-fill"></span> `$grapefruit`  | `hsl(10, 98%, 61%)`   | `#FD5A3B` |
| <span data-feather="droplet" class="salmon-fill"></span> `$salmon`          | `hsl(10, 98%, 61%)`   | `#FA9A87` |
| **Secondary colours**                                                                                           |
| <span data-feather="droplet" class="dark-green-fill"></span> `$dark-green`  | `hsl(180, 21%, 29%)`  | `#3A5959` |
| <span data-feather="droplet" class="mid-green-fill"></span> `$mid-green`    | `hsl(153, 39%, 45%)`  | `#47A178` |
| <span data-feather="droplet" class="light-green-fill"></span> `$light-green`| `hsl(91, 34%, 65%)`   | `#A3C386` |
| <span data-feather="droplet" class="yellow-fill"></span> `$yellow`          | `hsl(49, 93%, 65%)`   | `#F9D950` |

## Accessible combinations

Not all colours can be mixed together if we want content to be accessible for users with colour vision deficiencies (CVDs). Graphical and non-essential page elements (i.e. not required to understand the content) are not bound by these combinations.

The following are the acceptable (WCAG AA-compliant) combinations of colours for text and background.

<iframe title="Colour combinations on Figma" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FCLkv5unlaRSU5YABUNqN1v%2FBuilding-blocks%3Fnode-id%3D42%253A2" allowfullscreen></iframe>
