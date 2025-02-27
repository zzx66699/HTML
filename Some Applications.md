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

<h2>Chapter 5</h2>
<p>This chapter explains ba bla bla</p>

</body>
</html>
```
