<img width="533" alt="image" src="https://github.com/user-attachments/assets/38f50ca8-27d5-4a13-aa55-643729f6e7e5">

### A Simple HTML Document
HTML由element组成，element由自己的attribute
Always Quote Attribute Values
  
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
    <!-- #空一行 -->
    <br>

    <h1 style="font-size:60px;">Heading 1</h1>
    <h2>This is heading 2</h2>

    <p>My first paragraph.</p>
    <p style="color:red;">This is a red paragraph.</p>
    <p>This is a <br> paragraph with a line break.</p>
    <!-- In some situations, when the attribute value itself contains double quotes, it is necessary to use single quotes -->
    <p title="John 'ShotGun' Nelson">

    <!-- <a> 是超链接anchor标签, HTML links are defined with the <a> tag -->
    <a href="https://www.w3schools.com">This is a link</a>

    <img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">
</body>

</html>
```
