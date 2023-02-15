---
title: "Neo-System Font Stack"
---

A better, opinionated system font stack by [Benson Kitia](https://bensonkitia.com/).

[GitHub](https://github.com/bensonkitia/opensource.bensonkitia.com/blob/main/neo-system-font-stack/index.md) (PRs welcome!)

## Basic neo-system font stacks

### Sans-serif

`font-family: -apple-system, BlinkMacSystemFont, 'Helvetica Neue', 'Avenir Next', 'Avenir', 'Segoe UI', 'Helvetica', 'Cantarell', 'Ubuntu', 'Roboto', 'Noto', 'Arial', sans-serif;`

### Serif

`font-family: -apple-system-ui-serif, ui-serif, 'Iowan Old Style', 'Apple Garamond', 'Georgia', 'Baskerville', 'Times New Roman', 'Droid Serif', 'Times', 'Source Serif Pro', serif, 'Apple Color Emoji', 'Segoe UI Emoji', 'Segoe UI Symbol';`

### Monospace

`font-family: ui-monospace, SFMono-Regular, ui-monospace, 'Menlo', 'Consolas', 'Monaco', 'Liberation Mono', 'Lucida Console', monospace;`

## FAQ

### Why use system fonts?

#### Speed

**No network request, no time to parse a font, no flash of an incorrect font.**

If you're including fonts from TypeKit or Google, you're hitting another domain. So, they might hurt your site's ability to work offline, will require extra domain connections, and may require extra entries in your Content-Security-Policy. They also require extra time to parse and render, which can cause a flash of unstyled text (FOUT) or a flash of incorrect font (FOIT). System fonts, on the other hand, are already on the user's computer, so they don't require any network requests, and they're already parsed and ready to go. This means that your site will load faster, and will look better. (Note: this is not always the case, and you should test your site with a variety of network conditions to make sure it looks good.)

#### Styles & unicode

**System fonts have lots of styles and broad language coverage, unlike many webfonts.**

Webfonts often have a narrow range of glyphs included, so they can make your site's experience in non-English languages sub-par. System fonts, on the other hand, are usually designed to work with a wide range of languages, and often have a lot of styles available. Webfonts also tend to have a scarcity of weights, and in a lot of cases, you'll only tick off a few buttons for the weights you want to include, which means that your site will be missing styling - or even worse, synthesize faux-bold styles. Bad news! This means that with system fonts, your site will look better, and will be more accessible. (Note: this is not always the case, and you should test your site with a variety of languages to make sure it looks good.)

#### Familiarity

**Websites & web apps feel more native when they use system font faces.**

System fonts are the fonts that users are used to seeing on their devices. This means that your site will feel more familiar to your users.

### Are there disadvantages to using system fonts?

Sure! Here are some:

* Specifying system fonts on some platforms is just weird. -apple-system and so on.
* You can sometimes get another font of the same name that exists on someone's computer somewhere.
* You can't demonstrate your world-class taste for pleasant typography selection.

### Why this stack?

This stack, while derived from and very similar to the  [systemfontstack](https://systemfontstack.com/), is more opinionated, so it ultimately prioritizes *better looking* fonts over *more default* ones, while still providing the benefits listed above. The changes mostly affect Apple devices running recent-ish software. Notably, this stack uses:

* Helvetica Neue as a fallback to San Fransisco for sans-serif on all systems
* New York for serif (instead of Iowan Old Style) on Apple systems
* SF Mono for monospace (instead of Menlo) on Apple systems, with Georgia as the first fallback for non-Apple systems

Also, this stack tries its best to follow W3 spec and other conventions/best practices, somewhere the other one falls a bit short.

### What's -apple-system?

-apple-system and BlinkMacSystemFont are aliases for the default fonts on new macOS and iOS computers. In recent versions, they are an alias for the new San Francisco font.

## References

* [systemfontstack](https://systemfontstack.com/)
* [The New System Font Stack](https://bitsofco.de/the-new-system-font-stack/)
* [GitHub System Fonts](https://markdotto.com/2018/02/07/github-system-fonts/)
* [CSS System Font Stack - Monospace v1](https://www.client9.com/css-system-font-stack-monospace-v1/)
* [Implementing system fonts on Booking.com](https://booking.design/implementing-system-fonts-on-booking-com-a-lesson-learned-bdc984df627f)
* [Using Apple's New York font in CSS](https://matthew-jackson.com/blog/using-apples-new-york-font-in-css/)
