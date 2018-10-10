# Introduction
The website is divided into three parts:
    - `index.html`
    - `index.css`
    - `static/*`

`index.html` is the HTML markup for the website; whilst
`index.css` is its stylesheet. The `static` directory
should be used for hosting static content; the examples
of which include, but are in no way limited to, vendor-specific
libraries, static images, etc.

## `index.html`
The structure of the website is in compliance with the
requirements set forth in the document forwarded by
you in the email.

The `head` section provides you with all the required
meta information about the website: the title, viewport tags
the CSS link. 

Within the `body` section, I have wrapped three elements:
    - `header`
    - `main`

the semantics of which should be relatively simple
and straightforward to understand and interpret. 

### `header`
The `header` contains the first section of the website
and hence the name. I have generously used `clip-path`
which is a simple CSS rule to clip certain portions
of an element based on the bounding rules provided. 

The `image-crop` class is used for that rounded
effect on the picture. 

The `<i class="arrow">` tag is used for that downward
arrow made completely in CSS; no pictures, bhai. 

### `main`
The `main` section contains the primary content of
the website: the cards, and vis-a-vis, the portfolio.

The first `section`, called the `section__header` is,
you guessed it, the header of the entire section.

Moving down, `#portfolio` is basically where the entire
content lies. 

The generalized `portfolio__content` class is used 
for each of the cards you see on the viewport \(the window\).
The card has three things:
    - an image;
    - a block of text (from Wikipedia);
    - a name

You should copy and paste the `portfolio__content` as many
times as you want for the number of cards. Everything uses
flexbox as described.

## What's missing.
You should add a static footer and some other content. I have
given you a basic website to build on; shouldn't take you a lot
of time! 

Message me if you need any help! :D
