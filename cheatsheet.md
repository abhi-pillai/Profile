# HTML & CSS Cheat Sheet

> A quick reference for the most commonly used HTML tags and CSS properties.

---

# HTML

## Basic Structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <link rel="stylesheet" href="style.css">
</head>
<body>

</body>
</html>
```

---

# Head Tags

| Tag        | Purpose           |
| ---------- | ----------------- |
| `<title>`  | Browser tab title |
| `<meta>`   | Metadata          |
| `<link>`   | External CSS      |
| `<style>`  | Internal CSS      |
| `<script>` | JavaScript        |
| `<base>`   | Base URL          |

---

# Text Elements

| Tag             | Description       |
| --------------- | ----------------- |
| `<h1>` - `<h6>` | Headings          |
| `<p>`           | Paragraph         |
| `<br>`          | Line break        |
| `<hr>`          | Horizontal line   |
| `<strong>`      | Bold (important)  |
| `<b>`           | Bold              |
| `<em>`          | Italic (emphasis) |
| `<i>`           | Italic            |
| `<u>`           | Underline         |
| `<mark>`        | Highlight         |
| `<small>`       | Small text        |
| `<sub>`         | Subscript         |
| `<sup>`         | Superscript       |
| `<code>`        | Code              |
| `<pre>`         | Preformatted text |
| `<blockquote>`  | Quote             |
| `<span>`        | Inline container  |
| `<div>`         | Block container   |

Example

```html
<h1>Hello</h1>

<p>This is a paragraph.</p>

<strong>Important</strong>

<code>System.out.println();</code>
```

---

# Links

```html
<a href="https://example.com">Visit</a>

<a href="about.html">About</a>

<a href="#section1">Jump</a>

<a href="mailto:test@gmail.com">Email</a>

<a href="tel:+911234567890">Call</a>
```

---

# Images

```html
<img src="image.jpg"
     alt="Description"
     width="300">
```

Useful attributes

* src
* alt
* width
* height
* loading="lazy"

---

# Lists

## Ordered

```html
<ol>
    <li>Java</li>
    <li>Python</li>
</ol>
```

## Unordered

```html
<ul>
    <li>Apple</li>
    <li>Mango</li>
</ul>
```

## Description

```html
<dl>
    <dt>HTML</dt>
    <dd>Markup language</dd>
</dl>
```

---

# Tables

```html
<table>

<tr>
<th>Name</th>
<th>Age</th>
</tr>

<tr>
<td>John</td>
<td>22</td>
</tr>

</table>
```

Useful Tags

* table
* tr
* th
* td
* thead
* tbody
* tfoot

---

# Forms

```html
<form>

<label>Name</label>

<input type="text">

<input type="email">

<input type="password">

<input type="number">

<input type="date">

<input type="checkbox">

<input type="radio">

<select>

<option>India</option>

</select>

<textarea></textarea>

<button>Submit</button>

</form>
```

Common Input Types

* text
* password
* email
* number
* tel
* url
* search
* date
* datetime-local
* time
* color
* range
* file
* checkbox
* radio
* submit
* reset
* hidden

Useful attributes

* placeholder
* required
* readonly
* disabled
* maxlength
* minlength
* autofocus
* checked
* selected

---

# Semantic HTML

| Tag            | Purpose             |
| -------------- | ------------------- |
| `<header>`     | Header              |
| `<nav>`        | Navigation          |
| `<main>`       | Main content        |
| `<section>`    | Section             |
| `<article>`    | Independent content |
| `<aside>`      | Sidebar             |
| `<footer>`     | Footer              |
| `<figure>`     | Image container     |
| `<figcaption>` | Caption             |

---

# Multimedia

```html
<audio controls>
</audio>

<video controls width="400">
</video>

<iframe src=""></iframe>
```

---

# HTML Entities

| Symbol | Entity    |
| ------ | --------- |
| <      | `&lt;`    |
| >      | `&gt;`    |
| &      | `&amp;`   |
| "      | `&quot;`  |
| ©      | `&copy;`  |
| ₹      | `&#8377;` |

---

# CSS

---

## Syntax

```css
selector{

    property: value;

}
```

Example

```css
h1{

    color: red;

}
```

---

# Selectors

```css
* {}

h1 {}

.class {}

#id {}

div p {}

div > p {}

div + p {}

div ~ p {}

input[type="text"] {}

a:hover {}

li:first-child {}

li:last-child {}

p::before {}

p::after {}
```

---

# Colors

```css
color: red;

color: #ff0000;

color: rgb(255,0,0);

color: rgba(255,0,0,.5);

color: hsl(0,100%,50%);
```

---

# Background

```css
background:

background-color:

background-image:

background-size: cover;

background-repeat: no-repeat;

background-position: center;
```

---

# Text

```css
color:

font-size:

font-family:

font-weight:

font-style:

text-align:

text-decoration:

text-transform:

letter-spacing:

line-height:

word-spacing:
```

---

# Box Model

```css
width:

height:

padding:

border:

margin:
```

Example

```css
div{

    width:300px;

    padding:20px;

    border:2px solid black;

    margin:10px;

}
```

---

# Display

```css
display:block;

display:inline;

display:inline-block;

display:flex;

display:grid;

display:none;
```

---

# Position

```css
position:static;

position:relative;

position:absolute;

position:fixed;

position:sticky;
```

Also

```css
top:

left:

right:

bottom:

z-index:
```

---

# Flexbox

Container

```css
display:flex;

flex-direction:row;

justify-content:center;

align-items:center;

gap:20px;

flex-wrap:wrap;
```

Item

```css
flex:1;

order:2;

align-self:center;
```

---

# Grid

```css
display:grid;

grid-template-columns:1fr 1fr;

grid-template-rows:auto;

gap:20px;
```

---

# Overflow

```css
overflow:hidden;

overflow:auto;

overflow:scroll;
```

---

# Border

```css
border:1px solid black;

border-radius:10px;
```

---

# Shadows

```css
box-shadow:0 0 20px gray;

text-shadow:2px 2px 5px black;
```

---

# Cursor

```css
cursor:pointer;

cursor:not-allowed;
```

---

# Opacity

```css
opacity:0.5;
```

---

# Object Fit

```css
object-fit:cover;

object-fit:contain;
```

---

# Transition

```css
transition:0.3s;

transition:all .3s ease;
```

---

# Transform

```css
transform:scale(1.2);

transform:rotate(45deg);

transform:translateX(50px);

transform:skew(20deg);
```

---

# Animation

```css
@keyframes fade{

from{

opacity:0;

}

to{

opacity:1;

}

}

.box{

animation:fade 2s infinite;

}
```

---

# Pseudo Classes

```css
:hover

:active

:focus

:visited

:first-child

:last-child

:nth-child()

:not()
```

---

# Pseudo Elements

```css
::before

::after

::first-letter

::first-line

::selection
```

---

# Responsive Design

Viewport

```html
<meta name="viewport"
content="width=device-width, initial-scale=1.0">
```

Media Query

```css
@media (max-width:768px){

.container{

flex-direction:column;

}

}
```

---

# Common Units

| Unit | Meaning            |
| ---- | ------------------ |
| px   | Pixels             |
| %    | Percentage         |
| em   | Relative to parent |
| rem  | Relative to root   |
| vw   | Viewport width     |
| vh   | Viewport height    |
| fr   | Grid fraction      |

---

# Frequently Used CSS Properties

```css
width
height
min-width
max-width
min-height
max-height

margin
padding
border
border-radius

display
position

top
left
right
bottom

overflow

background
background-color

color

font-size
font-family
font-weight

text-align

line-height

letter-spacing

box-shadow

opacity

cursor

flex

grid

gap

transition

transform

animation

object-fit

visibility

z-index
```

---

# HTML Boilerplate Shortcut

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport"
content="width=device-width, initial-scale=1.0">
<title>Document</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<script src="script.js"></script>

</body>
</html>
```

---

# CSS Reset

```css
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}
```

---

# Quick Flex Center

```css
display:flex;
justify-content:center;
align-items:center;
```

---

# Quick Grid

```css
display:grid;
place-items:center;
```

---

# Center a Block

```css
margin:auto;
```

---

# Make Image Responsive

```css
img{
    max-width:100%;
    height:auto;
}
```

---

# Common HTML5 Tags

```
header
nav
main
section
article
aside
footer
figure
figcaption
details
summary
dialog
canvas
svg
video
audio
```

---

## Tips

* Prefer semantic HTML over excessive `<div>` usage.
* Use Flexbox for one-dimensional layouts and Grid for two-dimensional layouts.
* Use `rem` for scalable typography and spacing.
* Always include `alt` text for images.
* Apply `box-sizing: border-box` globally to simplify layout calculations.
* Keep HTML focused on structure and CSS focused on presentation.
