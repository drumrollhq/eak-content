# Content Overview

### How this document works:
Each item is a part of the game. The
highest level are broad topics, which go all the way down to individual
levels at the lowest level. After each item, there's a marker to show
the status of that part of the project. The markers are:

* *future* - this will be covered in the future, but we're unable to
    look into it now.
* *maybe* - We may or may not include this.
* *discuss* - needs a load more thinking before we can move forward
* *planned* - we know what we're doing, but nothing about how
* *draft* - we have a draft of this content written
* *poc* - we've got a proof-of-concept level to test the content out
* *written* - we've written all the content for this section
* *assets* - we have all the art assets / VOs for this section
* *implemented* - the assets and content have been smooshed together on
    a publishable level
* *published* - the level has been published. YAY!

If there's no status next to an entry, it means that we'll be working on
it soon but haven't got anything figured out yet.

Throughout this, you might come across little diagrams like this:
```
    ________________________
    |A                     |
   1|======             k  |
    |P k               ====|2
   3|====                  |
    |______________________|
```

These are little sketches of possible level layouts. Here, `A` is the
start position of Arca, `k` is the location of a kitten, and `P` is the
location of a portal.

### Content Overview

- [Setting the scene](sections/01-intro/overview.md) - probably split
    this over a couple of cutscenes
  - Where is the game set - *planned*
  - What's going on? Why? - *planned*
  - Who/what is Arca? - *planned*
- [Using the game](sections/02-tutorial/overview.md)
  - [Moving about](sections/02-tutorial/01-control-arca.md) -
      *published*
  - Jumping - *published* - *[merged with Moving About]*
  - [Portals / doors](sections/02-tutorial/02-using-portals.md) -
      *published*
  - Using the map - *future*
  - Quickly getting from place to place - *future*
  - [Editing levels](sections/02-tutorial/03-editing-levels.md) -
      *draft*
  - [Using the Editor and tutorial
      system](sections/02-tutorial/04-editor-tuts.md)
- [HTML Basics](sections/03-html-basics/overview.md):
  - What is HTML? Why does it exist?
  - HTML Structure - `<open> contennt </close>`
  - Semantic tags:
    - What are they? Can we think of a better word than 'semantic'? Why
        do we use semantic tags?
    - `<p>` - paragraph
    - `<h1>`, `<h2>`, `<h3>` - headings
    - `<header>`, `<section>`, `<footer>` - Semantic document sections -
        perhaps worth leaving til later, when nesting is introduced?
  - Attributes
    - What are attributes for?
    - Attribute structure - `<open key1="value1" key2="value2"> content
        </close>`
    - Links - `<a href="..."></a>`
    - Images - `<img src="...">` - why no closing tag?
    - Image width - `<img src="..." width="...">`
  - Semantic Attributes - *maybe*
    - OMG it's like semantic tags and attributes had a baby!
    - `<time datetime="..."> </time>`
  - Consolidation
- CSS Basics
- Advanced HTML

