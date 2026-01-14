# IMG
## alt text
```html
<img src="husky.png" alt="a cheeky smiling husky">
```

## role and aria-label when you can't use an HTML img tag
make the `container div and everything inside` treated as an image.  
```html
<!-- the screen reader will skip all the children content inside the container, so the aria-label needs to include the text inside.  -->
<div class="meme-container" role="img" aria-label="A cheeky smiling dog with text saying 'when the cat gets blamed for something you did'.">
    <div class="meme-text">
        <h1>
            When the cat gets blamed for something you did
        </h1>
    </div>
</div>
```
```css
.meme-container {
    background-image: url('husky.jpeg');
    background-size: cover;
}
```