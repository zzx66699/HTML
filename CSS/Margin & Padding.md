# Margin & Padding
## Margin collapse
When a child element touches its parent, the top and bottom margins will merge with the margins of the parent elements. 
```html
<header>
 <!-- h1 touches the header, the margin of h1 will affect header's margin -->
	<h1>BBC NEWS</h1>
    <p class="header-text">
		<a href="" class="selected">Home</a> | 
		<a href="">World</a> | 
		<a href="">USA</a> | 
		<a href="">Europe</a> | 
		<a href="">Asia</a> | 
		<a href="">Africa</a> | 
		<a href="">Climate</a>
    </p>
</header>
```

## Margin collapse solution
add padding to the parents element
```js
header{
    background-color: #b80000;
    padding: 15px 20px;
}
```

## Elements
### Block element
`<div>`,`<p>`,`<h1>` are all block element.  
They stack on top of each other.  
Set height and margin top and bottom. ✅

### Inline elements
`<a>`, `<span>` are inline elements.  
Sit side by side.  
Can't set height and margin top and bottom. ❌

### Inline-block elements
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