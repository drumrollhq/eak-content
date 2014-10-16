# 2.3 - Editing Levels - Tutorials

We need to introduce the concept of being able to edit the world of the
game you are playing. This is a pretty massive idea, so we'll need to
break it down to an extent.

Not being overwhelming here is hard - we need to show that edit view to
people and get them to change something without them getting lost.

## Draft
### Level - Editing Text I
* There are two ledges either side of the level, with a gap between
    them. Arce is on one side, and the kitten and portal are on the
    other:

    ```
        ______________________
        |                    |
        | A              k P |
        |===            =====|
        |                    |
        |____________________|
    ```
* The user tries to jump over to the other side, but falls and dies -
    *is this a good idea? Maybe we shouldn't force people to die as
    much?*
* They are prompted to edit the level. A stripped down version of the
    edit view comes up, with a really focussed guided tour type thing
    that demonstrates and walks them through:
  * Selecting the ledge they are on
  * Typing their name in to make the ledge longer
  * Typing some more stuff to make the ledge reach the other side
  * Pressing save to finish
* In this level, there is no mention of the fact that what is being
    edited is HTML

### Level - play
The next level the user comes to doesn't involve any coding. Something
like:
```
    ____________________
    |      k         P |
    | A   ===   k   ===|
    |===       ===     |
    |                  |
    |__________________|
```

### Level - Editing Text II
The level after that has a layout like this:
```
    ____________________
    |A                 |
   1|======         k  |
    |P k           ====|2
   3|====              |
    |__________________|
```

Here, the player has to make ledge 2 longer in order to be able to jump
from ledge 1 to ledge 2, then from ledge 2 to ledge 3.

### Level - Editing Text III
Removing text, rather than adding it:
```
    _______________
    |             |
    | P k         |
    |=====        |
    |=====        |
   1|=====        |
    |=====    A   |
    |===== =======|
```

Removing text from block 1 makes it smaller, raising up the floor that Arca is standing on

In all of these levels, there is a restricted, locked down version of
the editor being used. Only the contents of the ledges is editable - the
tags etc. are not.

