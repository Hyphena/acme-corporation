Markdown
===========

I am a paragraph in markdown with line
wrapping so fit in this width.
I am a continuation of the first paragraph
as there is no empty line before me.

I am the second paragraph.


I am the third one. Even though there are
two line breaks before me, this does not
create any newline characters. After me there
are two spaces before the newline character.
I have line break before me and even though
I am not a new paragraph, I do start on a
new line due to the manual line break via
spaces before the newline character.

Top Level H1
=============
H2
---

#Just a tag
Also a # tag.
# Alternate H1
## Alternate H2
### H3
###### H6

* This is a list element
+ This is also a list element
- This is also a list element
 - This is a sublist element
 + Also a sublist element
     + Sublist level 2
     1. Numbered sublist
     2. Next item
        3. Next indent level

1. Numbered sublist
2. Next item
     1. Next indent level
        * Sublist non numbered
3. Back

Horizontal Lines:

------------------------------------
.
***********************************
.
***
.

---

> Block Quote

## Inline Formatting

*Italics*

_Italics_

__Bold__

___Bold+Italics___

this_is_not_emphasis

~~Strikethough~~

Content with a -- (dash) and a --- (long dash).

[link](http://link/path/to/target)

[link](http://link/path/to/target "TITLE ON LINK")

[Shared Links with footnotes][target 1]

[Second shared link][target 1]

[target 1]

[target 1]: http://footnote.com

Sample inline code `a++` can be specified here.

![Alt Text](/image/logo.png "Optional Tooltip")

## Tables, Code Blocks and Task lists

    Name | Job
---------|------
    Alex | Web Developer
    Bob  | Sys Admin
    Gabby| Technical Writer

## Alternate Table

| Name | Manta |
| --- | --- |
| Alex | There must be a better way.|
| Bob | Play it safe. |
| Gabby | Try everything, but do what you like. |

## Acme Website task list

- [x] Get the home page up
- [x] Update Privacy Policy and Terms of Use
- [ ] Add the about page
- [ ] Start the blog
- [ ] Enable contact us

## Code block

```javascript
var x = 10;
x++;
console.log(x);
```

## Direct Emojis
Smile please :smile:

I :heart: Hugo

Wink :wink:

A link to [Emojis](#direct-emojis)


## Fractions

1/2

100/99

Not a Number/5

A link to [Fractions](#fractions)


## Definition Lists

Alex
: Hippy Web Developer
: Conservative

Gabby
: Cool Content Master
: Cautious