---
title: Sample .md file
date: '2016-03-08'
tags: ['markdown', 'code', 'features']
draft: false
summary: Example of a markdown file with code blocks and syntax highlighting
images: ['/static/images/twitter-card.png']
---

# Image

 <div className="my-1 w-full overflow-hidden px-2 xl:my-1 xl:w-1/2 xl:px-2">
    ![Github Traffic](/static/images/journey/salary.jpg)
  </div>

<div className="-mx-2 flex flex-wrap overflow-hidden xl:-mx-2">
  <div className="my-1 w-full overflow-hidden px-2 xl:my-1 xl:w-1/2 xl:px-2">
    ![Maple](/static/images/canada/maple.jpg)
  </div>
  <div className="my-1 w-full overflow-hidden px-2 xl:my-1 xl:w-1/2 xl:px-2">
    ![Lake](/static/images/canada/lake.jpg)
  </div>
  <div className="my-1 w-full overflow-hidden px-2 xl:my-1 xl:w-1/2 xl:px-2">
    ![Mountains](/static/images/canada/mountains.jpg)
  </div>
  <div className="my-1 w-full overflow-hidden px-2 xl:my-1 xl:w-1/2 xl:px-2">
    ![Toronto](/static/images/canada/toronto.jpg)
  </div>
</div>

## Headers

```
# This is a h1 tag

## This is a h2 tag

#### This is a h4 tag
```

# This is a h1 tag

## This is a h2 tag

#### This is a h4 tag

## Emphasis

```
_This text will be italic_

**This text will be bold**

_You **can** combine them_
```

_This text will be italic_

**This text will be bold**

_You **can** combine them_

## Lists

### Unordered

```
- Item 1
- Item 2
  - Item 2a
  - Item 2b
```

- Item 1
- Item 2
  - Item 2a
  - Item 2b

### Ordered

```
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
```

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

## Images

```
![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
Format: ![Alt Text](url)
```

![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

## Links

```
http://github.com - automatic!
[GitHub](http://github.com)
```

http://github.com - automatic!
[GitHub](http://github.com)

## Blockquotes

```
As Kanye West said:

> We're living the future so
> the present is our past.
```

As Kanye West said:

> We're living the future so
> the present is our past.

## Inline code

```
I think you should use an
`<addr>` element here instead.
```

I think you should use an
`<addr>` element here instead.

## Syntax highlighting

Here’s an example of how you can use syntax highlighting with [GitHub Flavored Markdown](https://help.github.com/articles/basic-writing-and-formatting-syntax/):

````
```js:fancyAlert.js
function fancyAlert(arg) {
  if (arg) {
    $.facebox({ div: '#foo' })
  }
}
```
````

And here's how it looks - nicely colored with styled code titles!

```js:fancyAlert.js
function fancyAlert(arg) {
  if (arg) {
    $.facebox({ div: '#foo' })
  }
}
```

## Footnotes

```
Here is a simple footnote[^1]. With some additional text after it.

[^1]: My reference.
```

Here is a simple footnote[^1]. With some additional text after it.

[^1]: My reference.

## Task Lists

```
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
```

- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

## Tables

You can create tables by assembling a list of words and dividing them with hyphens `-` (for the first row), and then separating each column with a pipe `|`:

```
| First Header                | Second Header                |
| --------------------------- | ---------------------------- |
| Content from cell 1         | Content from cell 2          |
| Content in the first column | Content in the second column |
```

| First Header                | Second Header                |
| --------------------------- | ---------------------------- |
| Content from cell 1         | Content from cell 2          |
| Content in the first column | Content in the second column |

## Strikethrough

Any word wrapped with two tildes (like `~~this~~`) will appear ~~crossed out~~.
