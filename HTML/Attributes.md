# Attribute
Always Quote Attribute Values

## role
```html
<!--                                       switch to indicate it is a switch on/off -->
<div="toggleTheme" onclick="toggleTheme()" role="switch" aria-checked="false" ta tabindex="0"bindex="0">
    Lidivde
</div>
```

#### 2. The src Attribute
The <img> tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed:
There are two ways to specify the URL in the src attribute:

1. Absolute URL - Links to an external image that is hosted on another website.  
   Example: src="https://www.w3schools.com/images/img_girl.jpg".

2. Relative URL - Links to an image that is hosted within the website.   
If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg".
If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

#### 3. The title Attribute
```html
<p title="I'm a tooltip">This is a paragraph.</p>
```

### Create a Bookmark in HTML
Use the id attribute (id="value") to define bookmarks in a page 这个id是给需要跳转的部分命名  
Use the href attribute (href="#value") to link to the bookmark 这个是跳转到那个地方去
```html
<!DOCTYPE html>
<html>
<body>
  <p><a href="#C4">Jump to Chapter 4</a></p>

  <h2>Chapter 1</h2>
  <p>This chapter explains ba bla bla</p>

  <h2>Chapter 2</h2>
  <p>This chapter explains ba bla bla</p>

  <h2>Chapter 3</h2>
  <p>This chapter explains ba bla bla</p>

  <h2 id="C4">Chapter 4</h2>
  <p>This chapter explains ba bla bla</p>
</body>
</html>
```


