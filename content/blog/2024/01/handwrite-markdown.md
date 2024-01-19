---
title: "Inkdown"
date: 2024-01-18T16:30:18-06:00
categories:
  - tools
tags:
  - markdown
  - notebooks
  - notes
  - writing
cover: "images/blog/inkdown/Field_Notes.JPG"
draft: false
---

I’ve started carrying a pocket notebook around for a more romantic, reliable ideation experience. It’s not for everything for everyone, but I like feeling my thoughts harder and having a physical representation of my thought process. Built-in indicators of an idea’s evolution are valuable. Literally, when the original form of a crossed-out idea is recovered rather than forever backspaced, and sentimentally as I flip through a patinated record of my progression. I found something powerful about an object that contains both my ideas and the their perspiration product.

[![A work environment with a MacBook Air displaying code on the screen, a coffee cup labeled "CONTENTS MAY BE HOT", and a "FIELD NOTES" memo book with a pen on a wooden table.](/images/blog/inkdown/Field_Notes.JPG)](https://fieldnotesbrand.com/products/chicago/?ref=kitia.net)

My back pocket won’t accommodate anything much bigger than Field Notes’ 3.5" × 5.5" (89mm × 140mm) original Memo Book, which is too small for readably writing nested thoughts with a traditional note-taking format. Headers were the most obviously problematic to format on an analog page, so using an increasing number of hashtags to differentiate them was a no-brainer. Shortly thereafter I jotted "*\# [video](https://www.youtube.com/@benkitia) [blogpost](https://www.kitia.net/blog) ideas*" on a fresh page and  *"\* handwriting in markdown*" on the following line.

## Markdown

[John Gruber](https://daringfireball.net)’s casual introduction of the greatest, holiest abstraction of a markup language ever:

> [Markdown is a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML).](https://daringfireball.net/projects/markdown/)

Basically, Markdown lets us type out the stuff on the left to get the stuff on the right:

![Screenshot showing a comparison between Markdown syntax on the left and the corresponding HTML code on the right.](/images/blog/inkdown/MD_to_HTML_demo.png "Markdown to HTML demo")

...which saves a lot of valuable time in not only writing but also resolving would-be syntax errors, so much so that it’s organically spread to what I’d guess is almost every engineering org. Gruber continues:

> [Thus, “Markdown” is two things: (1) a plain text formatting syntax; and (2) a software tool, written in Perl, that converts the plain text formatting to HTML.](https://daringfireball.net/projects/markdown/)

Until Field Notes includes a Perl interpreter in their notebooks, I’m discussing Markdown as its syntax, aptly “easy-to-read, easy-to-write plain text”.

## Inkdown

Branded “flavors” of markdown have emerged since 2004 to support more formatting features like highlighting, footnotes, and tables (of contents). Naming things is fun, so here I’m coining Inkdown, a flavor of “Markdown” for handwritten notes.

![A handwritten note on grid paper demonstrating Inkdown features, placed on a laptop keyboard, with sunlight casting shadows across the page.](/images/blog/inkdown/demo.JPG "Inkdown demo")

### Intuitive adaptation

Inkdown's parser (the writer’s brain) and spec (these loose suggestions) are as malleable as it gets, so your flavor is infinitely adaptable to the needs of any note or project. Here's my general application, which is readable to those familiar with common Markdown flavors but seeks to be compressible to save coveted space while maintaining readability.

#### Titles

Markdown titles work well spacially.

![Close-up photo of a handwritten note on grid paper: #Title 1, ##Title 2, and ###Title 3 on seperate lines](/images/blog/inkdown/titles.png "Titles")

#### Bullets

After `#`s for titles, the top-level bullet is represented by `*`, the next level `+`, followed by `-`, regressing in size as lines appear to be removed from the parent symbol with each indent.

This visual deconstruction can continue as additional levels of indentation are needed, using `•` and then `◦`.

[![an animation of a star, then plus, then dash, then bullet point, then open bullet point on graph paper](/images/blog/inkdown/bullets_deconstruction.gif "bullet point deconstruction")](https://berkeleygraphics.com/typefaces/berkeley-mono/?ref=kitia.net)

These symbols are visually distinct enough to make intuitively readable nested notes without leading whitespace.

#### Links

I find Markdown’s link syntax (`(link)[title]`) to be useful for remembering content I might need to reference later, like a specific podcast episode.

![Close-up photo of a handwritten note on grid paper with the text 'Implement Cal Newport’s organizational ideas)[Deep Questions Ep. 238).](#)](/images/blog/inkdown/links.png "Links")

#### Highlighting

I’ve adopted a common convention for highlighting text from various Markdown flavors, using equal signs `==like this==`. I prefer this to a highlighter because it enables differing levels of emphasis by adjusting the width (or even thickness) of the surrounding equal signs.

![Close-up photo of a handwritten note on grid paper demonstrating the use of varying widths of equal signs on either end of ideas for varying emphasis](/images/blog/inkdown/highlights.png "Highlighting")

This adaptability, now only permitted by handwriting, is a pure addition to Markdown’s functionality; Inkdown at its best.

#### Footnotes

![Handwritten note on grid paper stating "This has a footnote" with a footnote represented by superscript [1] and referenced at the bottom with “[1]: Reinventing the wheel rn!”](/images/blog/inkdown/footnotes.png "Footnotes")

This groundbreaking innovation to footnotes makes them, in my opinion, slightly easier to find and reference.
