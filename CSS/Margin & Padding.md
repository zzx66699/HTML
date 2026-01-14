# Margin & Padding
## Margin collapse
`All text elements` come with spacing on top and bottom by default.

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

