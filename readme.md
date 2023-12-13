# CSS Usage Guide

This guide provides a quick reference on how to use CSS (Cascading Style Sheets) to style HTML documents.

## Table of Contents
- [CSS Usage Guide](#css-usage-guide)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Basic CSS](#basic-css)
    - [Inline CSS](#inline-css)
    - [Internal CSS](#internal-css)
    - [External CSS](#external-css)
  - [Selectors I](#selectors-i)
  - [Selectors II (Pro max 😜 )](#selectors-ii-pro-max--)
    - [Attribute Selector:](#attribute-selector)
    - [Descendant Selector:](#descendant-selector)
    - [Child Selector (`>`):](#child-selector-)
    - [Adjacent Sibling Selector (`+`):](#adjacent-sibling-selector-)
  - [Properties](#properties)
      - [Text Properties](#text-properties)
      - [Background Properties](#background-properties)
      - [Border Properties](#border-properties)
      - [Other Properties](#other-properties)
  - [Box Model](#box-model)


## Introduction
CSS is a stylesheet language used for describing the presentation of a document written in HTML. It allows you to control the layout, style, and appearance of your web pages.

## Basic CSS

### Inline CSS
You can apply styles directly to HTML elements using the `style` attribute.

```html
<p style="color: red; font-size: 16px;">This is a red paragraph with a font size of 16 pixels.</p>
```

### Internal CSS

Internal CSS is defined within the `<style>` tag in the head of the HTML document.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      background-color: #f0f0f0;
    }

    h1 {
      color: blue;
    }
  </style>
  <title>My Website</title>
</head>
<body>
  <h1>Welcome to My Website</h1>
</body>
</html>

```


### External CSS

External CSS is stored in a separate file and linked to the HTML document.

styles.css:

```html

 /* styles.css */
body {
  background-color: #f0f0f0;
}

h1 {
  color: blue;
}
```

index.html:


```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="styles.css">
  <title>My Website</title>
</head>
<body>
  <h1>Welcome to My Website</h1>
</body>
</html>

```



## Selectors I

CSS selectors are patterns used to select and style HTML elements. Common selectors include element selectors, class selectors, and ID selectors.

```html

/* Element Selector */
p {
  color: green;
}

/* Class Selector */
.my-class {
  font-size: 18px;
}

/* ID Selector */
#my-id {
  border: 1px solid black;
}


```

## Selectors II (Pro max 😜 )

### Attribute Selector:

Selects elements based on the presence or value of their attributes.

Example:

```html

[aria-hidden="true"] {
  display: none;
}

```

### Descendant Selector:

Selects all child elements of a particular parent element.

Example:

```html

div.row * {
  margin: 5px;
}


```

### Child Selector (`>`):

Selects only the direct children of an element.

Example:

```html

ul > li {
  list-style-type: square;
}

```


### Adjacent Sibling Selector (`+`):

Selects the first element that is immediately preceded by a specified element.

Example:

```html

li + a {
  color: red;
}

```

## Properties

CSS properties define the style of an element. Some common properties include `color`, `font-size`, `margin`, `padding`, and more.


CSS properties define the style of an element. Here are some commonly used properties:

#### Text Properties
- `color`: Sets the color of text.
- `font-family`: Specifies the font for text.
- `font-size`: Sets the size of the font.
- `font-weight`: Defines the thickness of the font.
- `text-align`: Aligns text horizontally.
- `text-decoration`: Adds decoration to text (underline, overline, line-through).

#### Background Properties
- `background-color`: Sets the background color of an element.
  - Example: `background-color: #e0e0e0;`
- `background-image`: Sets the background image of an element.
  - Example: `background-image: url('background.jpg');`
- `background-repeat`: Specifies how a background image should be repeated.
  - Example: `background-repeat: repeat-x;`
- `background-position`: Sets the starting position of a background image.
  - Example: `background-position: center top;`

#### Border Properties
- `border`: Sets the border of an element.
  - Example: `border: 2px solid #333;`
- `border-radius`: Defines the curvature of an element's corners.
  - Example: `border-radius: 10px;`
- `box-shadow`: Adds a shadow effect to an element.
  - Example: `box-shadow: 5px 5px 10px #888888;`
- `outline`: Sets the outline of an element.
  - Example: `outline: 2px dashed red;`

#### Other Properties
- `cursor`: Sets the type of cursor to be displayed when pointing over an element.
  - Example: `cursor: pointer;`
- `opacity`: Sets the transparency level of an element.
  - Example: `opacity: 0.8;`


## Box Model


The box model describes how elements are rendered on the web page. It consists of content, padding, border, and margin.

```html
/* Box Model Example */
.box {
  width: 200px;
  height: 100px;
  padding: 10px;
  border: 2px solid #333;
  margin: 20px;
}

```

<img src="./data/box-model-1.png"/>