# Decoration

## width
use `percentage` for responsive design  
It always takes the percentage of width of its parent container
### Progress bar
```html
<!-- Progress container -->
<div class="prog-container">
      <div class="prog-bar">
            <div class="prog-indicator prog-33"></div>
      </div>
</div>

<!-- Progress container -->
<div class="prog-container">
      <div class="prog-bar">
            <div class="prog-indicator prog-60"></div>
      </div>
</div>
```
```css
/* for the whole bar */
.prog-bar {
    height: 20px;
    background-color: #808CB0;
    overflow: hidden;
    border-radius: 12px;
}

/* for the highlighted part */
.prog-indicator {
    height: 100%;
    background-color: hotpink;
}

/* for the different percentage for bars */
.prog-33 {
    width: 33%;
}

.prog-60 {
    width: 60%;
}
```


## font from Google
```html
<!-- get the font weight 300 and 900 -->
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;900&display=swap" rel="stylesheet">
```



## underline
```css
a {
	text-decoration:underline dotted;
}
```



## Links and buttons
- links are for navigation, go to another location.  
- Buttons are for interaction. (Open a model)  
You can style the link like a button.