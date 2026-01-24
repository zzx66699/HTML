## font-size
### the rem unit - root em
We use `rem` for font-size to avoid the `compounding issue`.
1rem = 16px
```css
p {
      font-size: 1rem;
}
```
Only if we change the html font-size, 1rem will change  
```css
html {
    font-size: 20px;
}
```
### the em unit
A font-size value set in em is relative to the font size of the parent element.
If there's no font-size set for all the parents' elements, it will take `16px` as the default 1em.  

It is not commonly used because of the compounding issues.

## margin & padding & gap
### the em unit
A margin / padding set in em is relative to the font size of the current element. We use `em` because it is proportional scaling.  

```css
h1 {
    font-size: 1.25em;  /* 36px */
    margin: 1em;   /* 36px */
    padding: 1.25em;  /* 36px * 1.25 */
}
```
### Button Example
For buttons, usually we can set `1em` for the right and left padding, and `0.5em` for the top and bottom padding to make sure everything is proportionate.   

For the margin between buttons, it can be the same.  
```css
.btn {
    font-size: 1.125em;
    padding: 0.5em 1em;
    margin-right: 0.5em;
    margin-bottom: 1em;
```

## line-height
Set the line height a `unitless` value which is approximately 1.5 times of the font size.  
```css
p {
    line-height: 1.5;
}
```

## width
use %  

## max-width
use px