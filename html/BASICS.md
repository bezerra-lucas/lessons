# Introduction to HTML Basics

HTML, or Hypertext Markup Language, is the standard markup language used to create and design web pages. It uses a system of tags and attributes to structure content on the web. This tutorial will cover the basics of HTML and help you get started with creating your own web pages.

## Table of Contents 
- [Introduction to HTML Basics](#introduction-to-html-basics)
  - [Table of Contents](#table-of-contents)
  - [1. HTML Structure](#1-html-structure)
  - [2. HTML Tags](#2-html-tags)
  - [3. HTML Attributes](#3-html-attributes)
  - [4. HTML Headings and Paragraphs](#4-html-headings-and-paragraphs)
  - [5. HTML Links](#5-html-links)
  - [6. HTML Images](#6-html-images)
  - [7. HTML Lists](#7-html-lists)
  - [8. HTML Tables](#8-html-tables)
  - [Conclusion](#conclusion)

<a name="html-structure"></a>

## 1. HTML Structure

An HTML document consists of a structure that includes an opening and closing tag, the doctype declaration, and the head and body sections. Here's a simple example:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Web Page</title>
  </head>
  <body>
    <h1>Hello, World!</h1>
    <p>Welcome to my web page.</p>
  </body>
</html>
```

<a name="html-tags"></a>

## 2. HTML Tags

HTML tags are used to define elements in an HTML document. They typically come in pairs: an opening tag and a closing tag. For example:

```html
<p>This is a paragraph.</p>
```

Some tags, like `<img>` and `<br>`, are self-closing and don't require a separate closing tag.

<a name="html-attributes"></a>
## 3. HTML Attributes

Attributes are used to provide additional information about HTML elements. They are placed within the opening tag of an element. For example:

```html
<a href="https://www.example.com">Visit Example.com</a>
```

<a name="html-headings-and-paragraphs"></a>
## 4. HTML Headings and Paragraphs

Headings and paragraphs are essential for structuring content on a web page. Headings are defined using `<h1>` to `<h6>` tags, with `<h1>` being the largest and `<h6>` being the smallest. Paragraphs are defined using the `<p>` tag.

```html
<h1>Main Heading</h1>
<p>This is a paragraph.</p>
```

<a name="html-links"></a>

## 5. HTML Links

Links are created using the `<a>` tag, with the `href` attribute specifying the destination URL.

```html
<a href="https://www.example.com">Visit Example.com</a>
```

<a name="html-images"></a>

## 6. HTML Images

Images can be added to a web page using the `<img>` tag. The `src` attribute is used to specify the image source URL, and the `alt` attribute provides alternative text for accessibility purposes.

```html
<img src="image.jpg" alt="An example image" />
```



<a name="html-lists"></a>
## 7. HTML Lists

HTML supports two types of lists: ordered lists and unordered lists. Ordered lists use the `<ol>` tag, while unordered lists use the `<ul>` tag. List items are created using the `<li>` tag.

```html
<ol>
  <li>First item</li>
  <li>Second item</li>
</ol>

<ul>
  <li>Item A</li>
  <li>Item B</li>
</ul>
```

<a name="html-tables"></a>

## 8. HTML Tables

Tables are used to display data in rows and columns. They are created using the `<table>` tag, along with `<tr>` for table rows, `<th>` for table headers, and `<td>` for table data cells.

```html
<table>
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
  </tr>
  <tr>
    <td>Row 1, Cell 1</td>
    <td>Row 1, Cell 2</td>
  </tr>
  <tr>
    <td>Row 2, Cell 1</td>
    <td>Row 2, Cell 2</td>
  </tr>
</table>
```


## Conclusion

This tutorial covered the basics of HTML, including its structure, tags, attributes, and common elements such as headings, paragraphs, links, images, lists, and tables. With these foundational concepts, you can start building your own web pages and continue learning more advanced HTML techniques.