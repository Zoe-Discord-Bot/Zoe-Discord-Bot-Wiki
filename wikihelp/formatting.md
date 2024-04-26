---
title: timfernix' Wiki/Markdown/HTML help
description: 
published: true
date: 2024-04-26T15:37:41.848Z
tags: 
editor: markdown
dateCreated: 2023-09-13T20:20:07.754Z
---

# Headline H1 (Headlines)
`# Headline H1`
## Headline H2
`## Headline H2`
### Headline H3
`### Headline H3`
#### Headline H4
`#### Headline H4`
##### Headline H5
`##### Headline H5`
###### Headline H6
`###### Headline H6`

# Text formatting
**Bold text**
`**Bold text**`

---
*Italic text*
`*Italic text*`

---
_Underlined text_
`_Underlined text_`

---
~~Strikethrough text~~
`~~Strikethrough text~~`

---
Text ^Superscript^
`Text ^Superscript^`

---
Text ~Subscript~
`Text ~Subscript~`

---
<kbd>Keyboard keys</kbd>
`<kbd>Keyboard keys</kbd>`

---
`Inline code` 
<p> `Inline code` </p>

---

```
code blocks
```

<p>```<br>
code blocks<br>
``` </p>

---

# Lists & Tables
1. Ordered List Item 1
2. Ordered List Item 2
3. Ordered List Item 3
```
1. Ordered List Item 1
2. Ordered List Item 2
3. Ordered List Item 3
```

---
- Unordered List Item 1
- Unordered List Item 2
- Unordered List Item 3
```
- Unordered List Item 1
- Unordered List Item 2
- Unordered List Item 3
```
---
| Table column 1 | Table column 2 |
|----------|----------|
| Cell 1      | Cell 2      |
| Cell 3      | Cell 4      |

```
| Table column 1 | Table column 2 |
|----------|----------|
| Cell 1      | Cell 2      |
| Cell 3      | Cell 4      |
```
---

- [Linklist Caption 1]()
- [Linklist Caption 2 *Description text*]()
- [:globe_with_meridians: With Emojis *and text.*]() 
{.links-list}
```
- [Linklist Caption 1]()
- [Linklist Caption 2 *Description text*]()
- [:globe_with_meridians: With Emojis *and text.*]() 
{.links-list}
```
---
- ![](/zoe_logo.png =24x) Images & Text  in grid lists
- ![](/zoe_logo.png =24x) Images & Text  in grid lists
- ![](/zoe_logo.png =24x) Images & Text  in grid lists
{.grid-list}

```
- ![](/zoe_logo.png =24x) Images & Text  in grid lists
- ![](/zoe_logo.png =24x) Images & Text  in grid lists
- ![](/zoe_logo.png =24x) Images & Text  in grid lists
{.grid-list}
```
---
- [x] Checked task item

- [x] Another checked task item

- [ ] Unchecked task item
```

- [x] Checked task item

- [x] Another checked task item

- [ ] Unchecked task item
```

# Assets & Links

![Asset](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/800px-Markdown-mark.svg.png =100x)

`![Asset](link.png)` OR `<img src="link.png" width="px">`

---
[Link Caption](Link)
`[Link Caption](Link)`

---

:smile: Emojis
`:smile: Emojis`

---

<i class="mdi mdi-information-outline"></i> *(mdi icons & captions)*{.caption .red--text}
```
<i class="mdi mdi-information-outline"></i> 
*(mdi icons & captions)*{.caption .red--text}
```

# Blockquotes

> Default block quote

`> Default block quote`

> Information block quote {.is-info}

`> Information block quote {.is-info}`

> Warning block quote {.is-warning}

`> Warning block quote {.is-warning}`

> Danger block quote {.is-danger}

`> Danger block quote {.is-danger}`

> Success block quote{.is-success}

`> Success block quote{.is-success}`

<br>

# Tabsets (Element)

# Tabsets {.tabset}
## **Tab 1**
Tabset Description

## **Tab 2** {.active}
Tabset Description
  
# Tabsets (Code)
```
# Tabsets {.tabset}
## **Tab 1**
Tabset Description

## **Tab 2** {.active}
Tabset Description
```

# Other
Footnotes [^1]
[^1]: Footnote 
```
Footnotes [^1]
[^1]: Footnote 
```
