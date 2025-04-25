---
title: Markdown Guide
slug: 'markdown-guide'
author: 'David R. Worman'
date: ''
categories:
 - Resources
tags:
 - Markdown
 - Resources
draft: 'false'
---

This Markdown Guide was heavily adapted from the [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) by [Adam Pritchard](https://github.com/adam-p) and is modified under its' License: [CC-BY](https://creativecommons.org/licenses/by/3.0/)


This Markdown Guide is intended as a quick reference and showcase of the markdown that is supported by both [Hugo](https://gohugo.io/) and the [Hugo Minivox](https://github.com/drworman/hugo-minivox) theme. This may not be a comprehensive list, but if it is here it *should* work for you.

---

## Headers

```markdown
# H1

## H2

### H3

#### H4

##### H5

###### H6

Alternatively, for H1 and H2, an underline-ish style:

# Alt-H1

## Alt-H2
```

# H1

## H2

### H3

#### H4

##### H5

###### H6
---
## Emphasis
```markdown
Emphasis, aka italics, with _asterisks_.

Strong emphasis, aka bold, with ***asterisks***.
```

Emphasis, aka italics, with _asterisks_.

Strong emphasis, aka bold, with ***asterisks***.

---
## Lists

(In this example, leading and trailing spaces are shown with with dots: ⋅)

```markdown
1. First ordered list item
2. Another item
   ⋅⋅\* Unordered sub-list.
3. Actual numbers don't matter, just that it's a number
   ⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅

- Unordered list can use asterisks

* Or minuses

- Or pluses
```

1. First ordered list item
2. Another item

- Unordered sub-list.

1. Actual numbers don't matter, just that it's a number
1. Ordered sub-list
1. And another item.

   You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

   To have a line break without a paragraph, you will need to use two trailing spaces.
   Note that this line is separate, but within the same paragraph.

- Unordered list can use asterisks

* Or minuses

- Or pluses

---
## Links

There are two ways to create links.

```markdown
[Inline-style link](https://www.google.com)

URLs and URLs in angle brackets will automatically get turned into links in the preview.
http://www.example.com or <http://www.example.com>
```

[Inline-style link](https://www.google.com)

URLs and URLs in angle brackets will automatically get turned into links in the preview.
http://www.example.com or <http://www.example.com>

---
## Images

```markdown
![alt text](image.png "Title")
```

![Jazz](/images/jazz.png "Jazz aka Solo Jazz")

---
## Inline code and code blocks

```markdown
Inline `code` has `backticks around` it.
```

Inline `code` has `backticks around` it.

Blocks of code are either fenced by lines with three backticks, or are indented with four spaces.

### 4-Spaces fence

```markdown
    s = "Code with space indent"
    print s
```

    s = "Code with space indent"
    print s

### Backtick fence

    ```
    Code goes here
    Code goes here
    ```

```
Code goes here
Code goes here
```
---
## Tables

```markdown
Colons can be used to align columns.

| Tables        |      Are      |  Cool |
| ------------- | :-----------: | ----: |
| col 3 is      | right-aligned | $1600 |
| col 2 is      |   centered    |   $12 |
| zebra stripes |   are neat    |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the
raw Markdown line up prettily. You can also use inline Markdown.

| Markdown | Less      | Pretty     |
| -------- | --------- | ---------- |
| _Still_  | `renders` | **nicely** |
| 1        | 2         | 3          |
```

Colons can be used to align columns.

| Tables        |      Are      |  Cool |
| ------------- | :-----------: | ----: |
| col 3 is      | right-aligned | $1600 |
| col 2 is      |   centered    |   $12 |
| zebra stripes |   are neat    |    $1 |

There must be at least 3 dashes separating each header cell. The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

| Markdown | Less      | Pretty     |
| -------- | --------- | ---------- |
| _Still_  | `renders` | **nicely** |
| 1        | 2         | 3          |

---
## Blockquotes

```markdown
> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can _put_ **Markdown** into a blockquote.
```

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can _put_ **Markdown** into a blockquote.

---
## Horizontal Rule
`* Note: the MinTD theme formats every Horizontal Rule as a dashed line.`
```markdown
Three or more...

---

Hyphens

***

Asterisks

___

Underscores
```

Three or more...

---

Hyphens

***

Asterisks

___

Underscores

---
## Line Breaks

```markdown
Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a _separate paragraph_.

This line is also begins a separate paragraph, but...
This line is only separated by two trailing spaces and a single newline, so it's a separate line in the _same paragraph_.
```

Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a _separate paragraph_.

This line is also begins a separate paragraph, but...
This line is only separated by two trailing spaces and a single newline, so it's a separate line in the _same paragraph_.

---
## Checkbox lists

```markdown
- [x] done
- [ ] todo
```

- [x] done
- [ ] todo
