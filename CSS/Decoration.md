# Decoration

## font from Google
```html
<!-- get the font weight 300 and 900 -->
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;900&display=swap" rel="stylesheet">
```
### form doesn't inherit the font family
```css
input {
    font-family: inherit;
}
```


## underline
```css
a {
	text-decoration:underline dotted;
}
```
## text-transform
```css
.headline {
     text-transform: uppercase;  /* lowercase, capitalize */
}
```

## background
```css
.container {
	/* always put a background color simlar to the image color */
    background: #9480e4 url("images/intro-bg.png");
    background-size: cover;
}

```

## Links and buttons
- links are for navigation, go to another location.  
- Buttons are for interaction. (Open a model)  
You can style the link like a button.