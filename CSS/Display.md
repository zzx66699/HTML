# Display

## Block element
`<div>`,`<p>`,`<h1>` are all block element.  
They stack on top of each other.  
Set height and margin top and bottom. ✅

## Inline elements
`<a>`, `<span>` are inline elements.  
Sit side by side.  
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