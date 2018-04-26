<!-- page_number: true -->

<img src="markdown.png" width="220">

_Markdown:_ a quick tutorial 
===

###### Adapted from https://guides.github.com/features/mastering-markdown/
###### Presented by Gaurav Trivedi ([@trivedigaurav](https://twitter.com/trivedigaurav))

---

# What is Markdown

- A simple way to format text
- Plain text with some extra symbols: `*`, `_`, `#` etc.
- Supports formatting text- **bold** or _italic_, adding images <img src="markdown.png" width="28">, 
	- and creating lists etc.
- Plus emojis :heart:

- Websites like [GitHub](github.com), [Reddit](reddit.com) use  it

> Some other ways to format text: _WikiSyntax, HTML, Word..._

---

# Basic Text

```
Easy to make words **bold** and *italic* with Markdown. 
Also add links: [GitHub.com](http://github.com)
```

Simple formatting **bold** and *italic* with Markdown. 
Adding links: [GitHub.com](http://github.com)

---

# Lists

```
1. Number one
2. Two

* Start with a star

- Or, dashes 
  - Like this
```

1. Number one
2. Two

* Start with a star

- Or, dashes 
  - Like this

---

# Images

```
![Markdown Logo](markdown.png)
```

![Markdown Logo](markdown.png)

---

# Headers and quotes

```
# Start lines with a `#` to create headings. 

### Multiple `##` in a row denote smaller heading sizes.

all the way up to six `######`.

> To quote someone, use the > character - Says me!
```
# Start lines with a `#` to create headings.  

### Multiple `##` in a row denote smaller heading sizes.

all the way up to six `######`.

> To quote someone, use the > character ~Says me!
---

# Code

Write code inline, `markdown = true`:
```
Write code inline, ```markdown=true```
```

Or, write code in-between backticks (```):
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.alert({div:'#foo'})
  }
  return true;
}
```
---

# Tables

```
First Header | Second Header
------------ | -------------
Cell 1 | Cell 2
First column | Second column
```

First Header | Second Header
------------ | -------------
Cell 1 | Cell 2
First column | Second column

---

## These slides were written in Markdown :+1:

#### Using [Marp](https://github.com/yhatt/marp), markdown presentation writer

#### https://github.com/gauravASC/markdown
