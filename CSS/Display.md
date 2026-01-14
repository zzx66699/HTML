# Display

## Block element
`<div>`,`<p>`,`<h1>` are all block element.  
They stack on top of each other.  
Set height and margin top and bottom. ✅

## Inline elements
`<a>`, `<span>`, `<img>` are inline elements.  
They sit side by side.  
They are given white space at the bottom to make sure the elements are not overalapped.   
Can't set height and margin top and bottom. ❌  

## Inline-block elements
`<button>`, `<input>` are inline elements.  
Sit side by side.  
Set height and margin top and bottom. ✅
```css
a{
    padding: 10px 19px;
    border-radius: 4px;
    background-color: #fff200;
    text-decoration: none;
	/* save the issue of overlapping buttons */
    display: inline-block;
	margin-top: 20px;
} 
```

## flex
The default behaviour of a child element of a flex box container is to `vertically stretch` to fill the container.  

We can use `align-self` property to limit the stretch

We can also use `margin` property to 
- limit the stretch
- push the element to a certain position
### align-self
It allows us to take a control of an **individual** element's alignment when it is inside a flex container. 
```css
button {
    align-self: center;
    align-self: flex-bottom;
    align-self: flex-start;
}
```

### margin auto on flexbox children
```css
.meme-container {
    display: flex;
}
.meme-text {
    /* set the margin property to auto opposite to the direction you want to push */
    margin: auto 0 0 auto; /* push the text to bottom right*/
}
```

## flex-wrap
```css
.thumbnails {
    display: flex;
    /* wrap child elements with a max width instead of just laying them out horizontally. */
    flex-wrap: wrap;
    max-width: 560px;
    margin: 50px auto;
}
```






