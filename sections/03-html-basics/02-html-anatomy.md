# 3.2 - Structure of a HTML element - HTML Basics

Here, we're introducing the basic structure of a HTML element. An opening tag, followed by some content, and finished with a closing tag:
```html
  <open> content </close>
```

This will set the foundation that the other levels in this section will build on, so it's important that we get it absolutely right. In these levels, we need to introduce the following terms:
- Tag
- Element
- Opening Tag
- Closing Tag

After playing, people should be able to recognize why these are wrong:
- `<p> hello`
- `<p< hello </p>`
- `<p> hello <p>`

And be able to write the correct `<p> hello </p>`.

At this stage, they do not need to know more than one type of HTML element.

## Draft
### Level - Creating elements I
```
    _____________________
    | A                 |
    |===                |
    |                   |
    |    ===            |
    |                   |
    |        xxx        |
    |             k     |
    |            xxx    |
    |                 P |
    |                ===|
    |___________________|
```

Here, the user needs to create two extra ledges in order to reach the kitten and the portal. A tutorial will guide them through creating a HTML element - first adding a opening `<p>`, then some content, then a closing `</p>`.

For the next element, the user is 'on their own' - although help should be available if needed.

### Level - Play I
A simple level that doesn't need much coding

TODO

### Level - Creating Elements II
```
    _____________________
    |               k P |
    |              =====|
    |               k   |
    |           ========|
    |               k   |
    | A                 |
    |===================|
    |___________________|
```

In this level, the player needs to create an extra element to complete the set of stairs and reach the kittens and portal.

### Level - Glitch setup
In code fixing levels, there are glitches all over the levels. I'm not sure what these look like yet. Perhaps they're sort of like black holes that consume your source code if you touch them, or something like that. Glitches are caused by errors in your code.

In this level, there's no coding and not much of a puzzle either. There's simply a bridge across some gap with a character who explains that the bridges ahead have been shoddily constructed or sabotaged by E.A.K. In order to cross the bridges, you'll need to fix the errors that are causing the glitches.

### Level - Glitch I
```
    _________________
    |               |
    | A    ggg g k P|
    |=== ==gg=g= ===|
    |    g   g gg   |
    |_______________|
```

In this level, glitches caused by errors in the levels code stop Arca from being able to cross the level. The code looks like this:

```html
  <p> Hello
```

Once the code is fixed, the glitches go away and Arca can safely cross the bridge.

### Level - Glitch II-IV
These levels have the same layout as Glitch I. However, in these, the broken code is as follows:

```html
  <p> Hello <p>
  <p< hello </p>
  <p> hello <p/>
```
