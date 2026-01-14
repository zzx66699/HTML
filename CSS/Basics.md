# Basics

## Organisation with comment
```css
body{
    font-size: 16px;
    color: #2b283a;
    font-family: 'Roboto', sans-serif;
    margin: 0;
}

/* typography */

h1{
    color: whitesmoke;
    font-size: 36px;
    margin: 0;
}

h2{
    margin: 0;
}

/* links */

a{
    color: #ef5839;
    text-decoration: underline dotted; 
}

a:hover{
    color: #d4b44c;
}

a:active{
    color: #d4b44c;
}

/* layout */

header{
    background-color: #5f29a3;
    padding: 45px 0;
}

section{
    padding: 45px 0;
}

.container{
    width: 620px;
    margin: 0 auto;
}

.main-image{
    width:100%;
}
```

## Overflow
```css
div {
    border: 2px solid black;
    font-size: 2rem;
    width: 70px;
    height: 200px;

    /* always add a scroll bar */
    overflow: scroll; 

    /* if the content exceeds the border of the container, add a scroll bar */
    overflow: auto; 

    /* if the content exceeds the border of the container, ignore the content */
    overflow: hidden;
    
    /* always show the content exceeding the border */
    overflow: visible;

    /* overflow-x: hidden and overflow-y:visible don't work together */
    overflow-x: hidden;
    overflow-y: visible;   /* ❌ */
}
```

## Float property
```css
img {
    height: 100px;
    border-radius: 10px;
    padding: 0;
    margin: 5px 10px 5px 0;
    /* img with text around it */
    float: right; 
}
```
```css
Remove any float
.para-1 {
    /* nothing will float to the right side of the element */
    clear: right;

    clear: both;
}
```
Contain the flow in the parent elements
```css
.para-3 {
    border: 1px solid;
    padding: 10px;
    /* ensure all the floated element is contained inside of parent element */
    display: flow-root;
}
```
