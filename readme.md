# HTML Basics

## Introduction

HTML, which stands for HyperText Markup Language, is the standard markup language used to create and design web pages. It forms the basic structure of a web page by defining various elements and their arrangement.

## HTML Document Structure

A minimal HTML document includes the following structure:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>

    <!-- Content goes here -->

</body>
</html>
```
- `<!DOCTYPE html>`: Declaration specifying the HTML version being used (HTML5).
- `<html>`: The root element wrapping the entire HTML document.
- `<head>`: Contains meta-information about the HTML document.
- `<title>`: Sets the title of the HTML document.
- `<body>`: Contains the content of the HTML document.

#### HTML Elements
HTML documents are built using HTML elements, defined by a start tag, content, and an end tag. For example:
```html
<p>This is a paragraph.</p>

```
- `<p>` is the start tag.
- `This is a paragraph.` is the content.
- `</p>` is the end tag.

#### Common HTML Elements
- #### Headings:
```html
<h1>This is a heading 1</h1>
```
<h1>This is a heading 1</h1>
<hr/>

```html
<h2>This is a heading 2</h2>
```
<h2>This is a heading 2</h2>

<hr/>
    
```html
<h3>This is a heading 3</h3>
```
<h3>This is a heading 3</h3>
<hr/>

```html
<h4>This is a heading 4</h4>
```
<h4>This is a heading 4</h4>
<hr/>

```html
<h5>This is a heading 5</h5>
```
<h5>This is a heading 5</h5>
<hr/>

```html
<h6>This is a heading 6</h6>
```
<h6>This is a heading 6</h6>
<hr/>

- #### Paragraphs:
```html
<p>This is a paragraph.</p>
```
<p>This is a paragraph.</p>
<hr/>

- #### Line Breaks:
```html
<p>This is a paragraph.<br>This is another paragraph.</p>
```
<hr/>

- #### Lists:
```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
</ul>

<ol>
  <li>Item 1</li>
  <li>Item 2</li>
</ol>
```
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
</ul>

<ol>
  <li>Item 1</li>
  <li>Item 2</li>
</ol>

<hr/>

- #### images:
```html
<img src="image.jpg" alt="Description of the image" />
```
<img src="https://www.microsoftissatso.tn/_next/image?url=%2Fimages%2Fmain-logo.png&w=96&q=75" alt="Description of the image" />
<hr/>

##### Attributes
HTML elements can have attributes that provide additional information about the element. For example
```html
<a href="https://www.example.com" target="_blank">Visit Example.com in a new tab</a>
```
Here, `href` is an attribute specifying the hyperlink, and `target="_blank"` is an attribute opening the link in a new tab.


This is a basic overview, and there are many more HTML elements and attributes to explore as you delve deeper into web development. HTML provides the foundation for building the structure of a web page, often combined with CSS for styling and JavaScript for interactivity.