## Document
https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements 

## A Simple HTML Document
  
``` html
<!-- a document type declaration, and helps browsers to display web pages correctly. -->
<!DOCTYPE html>

<!-- #root element of an HTML page, Country codes can also be added to the language code in the lang attribute. So, the first two characters define the language of the HTML page, and the last two characters define the country. -->
<html lang="en-US"> 

<!-- #用于存放网页的元信息（meta information），这些信息不会直接显示在网页的主体内容中，但会影响网页的行为和呈现方式 -->
<head> 
    <meta charset="UTF-8">
    <meta name="description" content="一个示例网页">
    <meta name="keywords" content="HTML, CSS, JavaScript">
    <!-- #标签页上的字-->
    <title>Page Title</title>  
    <link rel="stylesheet" href="styles.css">
    <script src="script.js"></script>
</head>

<body>
    <br>

    <h1 style="font-size:60px;">Heading 1</h1>
    <h2>This is heading 2</h2>

    <p>My first paragraph.</p>
    <p style="color:red;">This is a red paragraph.</p>
    <p>This is a <br> paragraph with a line break.</p>
    <!-- In some situations, when the attribute value itself contains double quotes, it is necessary to use single quotes -->
    <p title="John 'ShotGun' Nelson">

    <hr>

    <img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">
</body>

</html>
```

## Core tags
| Tag Name        | Meaning / Use                                                 | Attributes       | 
| --------------- | ------------------------------------------------------------- | ---------------- | 
| `<h1>` – `<h6>` | Headings — `<h1>` is the largest, `<h6>` the smallest.        |
| `<p>`           | Paragraph of text.                                            |
| `<div>`         | Division or container for grouping elements (block-level).    |
| `<button>`      | Clickable button.                                             |
| `<a>`           | Hyperlink (anchor).                                           | href target
| `<label>`       | Label for a form element.                                     |


| Tag Name        | Meaning / Use                                                 | Attributes       | 
| --------------- | ------------------------------------------------------------- | ---------------- | 
| `<img>`         | Image.                                                        | src
| `<input>`       | Input field (text box, checkbox, etc.).                       | type  placeholder



| Tag Name        | Meaning / Use                                                 | Attributes       | 
| --------------- | ------------------------------------------------------------- | ---------------- | 
| `<ul>`          | Unordered list (with bullet points).                          |
| `<ol>`          | Ordered list (with numbers).                                  |
| `<li>`          | List item (inside `<ul>` or `<ol>`).                          |

| Tag Name        | Meaning / Use                                                 | Attributes       | Usage       | 
| --------------- | ------------------------------------------------------------- | ---------------- | ----------- | 
| `<dl>`          | Description list.                                             |                  | metadata 
| `<dt>`          | Description term (inside `<dl>`).                             |                  |
| `<dd>`          | Description details (inside `<dl>`).                          |                  |


| Tag Name        | Meaning / Use                                                 | Attributes       | Usage       | 
| --------------- | ------------------------------------------------------------- | ---------------- | ----------- | 
| `<br>`          | Line break.                                                   |
| `<hr>`          | Horizontal line (divider).                                    |


## Formatting Elements

| Tag Name        | Meaning / Use                                                 | Attributes       | Usage       | 
| --------------- | ------------------------------------------------------------- | ---------------- | ----------- | 
| `<mark>`        | Highlight in yellow.                                          |                  | 
| `<strong>`          |                            |                  |
| `<b>`          |                           |                  |
| `<i>`          |                           |                  |
| `<em>`          |                           |                  |
| `<del>`          | Deleted text.                          |                  |
| `<ins>`          | Inserted text.                        |                  |
| `<sub>`          |                        |                  |
| `<sup>`          |                         |                  |


## Others
## Elements
| `<span>`        | Inline container for small pieces of text or elements.        |


| `<table>`       | Table container.                                              |
| `<tr>`          | Table row.                                                    |
| `<td>`          | Table cell (data).                                            |
| `<th>`          | Table header cell.                                            |
| `<form>`        | Form for user input.                                          |



| `<select>`      | Drop-down list.                                               |
| `<option>`      | Option inside a `<select>`.                                   |
| `<textarea>`    | Multi-line text input area.                                   |
| `<strong>`      | Important text (usually bold).                                |
| `<em>`          | Emphasized text (usually italic).                             |

| `<nav>`         | Navigation section (menu links).                              |
| `<header>`      | Header section of a page or article.                          |
| `<footer>`      | Footer section.                                               |
| `<section>`     | Logical section or topic block.                               |
| `<article>`     | A self-contained article (like a blog post).                  |
| `<main>`        | The main content area.                                        |
| `<video>`       | Embeds a video.                                               |
| `<audio>`       | Embeds an audio player.                                       |
| `<script>`      | JavaScript code.                                              |
| `<link>`        | Links to external resources (like CSS).                       |
| `<meta>`        | Metadata (charset, viewport, etc.).                           |