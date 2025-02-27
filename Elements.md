<img width="533" alt="image" src="https://github.com/user-attachments/assets/38f50ca8-27d5-4a13-aa55-643729f6e7e5">

### A Simple HTML Document
HTML由element组成，element由自己的attribute
  
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

### 1. pre for preformat
it defines preformatted text.  
The text inside is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks 可以用于展示诗歌
```html
<pre>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</pre>
```
<img width="317" alt="image" src="https://github.com/user-attachments/assets/7d7022c2-1c04-45ae-b7eb-09952626f38a" />

###  2. hr for 分割线 & br for 换行
<img width="1420" alt="image" src="https://github.com/user-attachments/assets/37f3b539-ae60-4467-b9c9-0f42f7032728" />

### 3. Formatting Elements
```html
<!-- 加粗 -->
<strong>This text is important!</strong>
<b>This text is important!<b>

<!-- 斜体 -->
<i>This text is italic</i>
<em>This text is emphasized</em>

<p>Do not forget to buy <mark>milk</mark> today.</p>

<!-- strike 和 underscore -->
<p>My favorite color is <del>blue</del> <ins>red</ins>.</p>


<p>This is <sub>subscripted</sub> text.</p>
<p>This is <sup>superscripted</sup> text.</p>
```
<img width="619" alt="image" src="https://github.com/user-attachments/assets/3f209862-812c-4e51-9731-724db94cbda6" />

### 4. a for anchor link 超链接
```html
<!-- HTML links are defined with the <a> tag -->
    <a href="https://www.w3schools.com">This is a link</a>
```

### 5. Quotations
1. blockquote element defines a section that is quoted from another source.  
Browsers usually indent blockquote elements. 缩进
<img width="1396" alt="image" src="https://github.com/user-attachments/assets/a443ba21-b9a9-404b-84e9-068965ea7730" />

2. q tag defines a short quotation.  
Browsers normally insert quotation marks around the quotation. 打引号
<img width="1327" alt="image" src="https://github.com/user-attachments/assets/2ac1e3ed-e640-4899-a5b7-b20ea9b2e5de" />

### 6. abbr elemenet for abbreviations
Use the global title attribute to show the description for the abbreviation/acronym when you mouse over the element. 
```html
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
```
<img width="250" alt="image" src="https://github.com/user-attachments/assets/2f6a5da7-f015-45da-8a6a-79d72df8d55e" />

### 7. address for address
The contact information can be an email address, URL, physical address, phone number, social media handle, etc.
```html
<address>
Written by John Doe.<br>
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>
```
### 8. cite for Work Title
defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.).
```html
<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>
```

### 9. Internal CSS & External CSS
```html
<!DOCTYPE html>
<html>
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

### bdo for Bi-Directional Override 换一个方向解读
```html
<bdo dir="rtl">This text will be written from right to left</bdo>
```
<img width="316" alt="image" src="https://github.com/user-attachments/assets/6f775af7-0727-43fc-94dd-113966ec1023" />
