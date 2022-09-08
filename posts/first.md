---
title: My First Blog Post
description: This is the first post on my blog
tags: post
date: 2021-06-19
layout: layouts/post.njk
---

# Заголовок 1

## Заголовок 2

### Заголовок 3

#### Заголовок 4

##### Заголовок 5

###### Заголовок 6

_Курсив_

**Жирным**

~~Перечеркнуты~~

1. First ordered list item
2. Another item
3. Actual numbers don't matter, just that it's a number
4. And another item.

- item
- item
- item

[I'm an inline-style link](https://www.google.com)

![alt text][logo]

[logo]: https://images.unsplash.com/photo-1662220213379-6463b026d6cf

Inline `code` has `back-ticks around` it.

```javascript
var s = 'JavaScript syntax highlighting';
alert(s);
```

```typescript
class MyClass {
	public static myValue: string;
	constructor(init: string) {
		this.myValue = init;
	}
}
```

```xml
<!DOCTYPE html>
<title>Title</title>

<style>body {width: 500px;}</style>

<script type="application/javascript">
  function $init() {return true;}
</script>

<body>
  <p checked class="title" id='title'>Title</p>
  <!-- here goes the rest of the page -->
</body>
```

```xml
<!DOCTYPE html>
<title>Title</title>

<style>body {width: 500px;}</style>

<script type="application/javascript">
  function $init() {return true;}
</script>

<body>
  <p checked class="title" id='title'>Title</p>
  <!-- here goes the rest of the page -->
</body>
```

```css
@font-face {
	font-family: Chunkfive;
	src: url('Chunkfive.otf');
}

body,
.usertext {
	color: #f0f0f0;
	background: #600;
	font-family: Chunkfive, sans;
	--heading-1: 30px/32px Helvetica, sans-serif;
}

@import url(print.css);
@media print {
	a[href^='http']::after {
		content: attr(href);
	}
}
```

```coffescript
grade = (student, period=(if b? then 7 else 6)) ->
  if student.excellentWork
    "A+"
  else if student.okayStuff
    if student.triedHard then "B" else "B-"
  else
    "C"

class Animal extends Being
  constructor: (@name) ->

  move: (meters) ->
    alert @name + " moved #{meters}m."
```

```
No language indicated, so no syntax highlighting.
But let's throw in a <b>tag</b>.
```

Colons can be used to align columns.

| Tables        |      Are      | Cool |
| ------------- | :-----------: | ---: |
| col 3 is      | right-aligned |      |
| col 2 is      |   centered    |      |
| zebra stripes |   are neat    |      |

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can _put_ **Markdown** into a blockquote.

Three or more...

---
