## font-size
Change all font-size properties from px to rem, letting the user to change the default page sizing by zooming in and zooming out. 
1rem = 16px
```css
p {
      font-size: 1rem;
}
```
## the em unit
### font-size
**A font-size value set in em is relative to the font size of the parent element.**  
If there's no font-size set for all the parents' elements, it will take `16px` as the default 1em.  

### margin & padding & gap
**A margin / padding set in em is relative to the font size of the current element.**  
```css
h1 {
    font-size: 1.25em;  /* 36px */
    margin: 1em;   /* 36px */
    padding: 1.25em;  /* 36px * 1.25 */
}
```
#### Button
For buttons, usually we can set `1em` for the right and left padding, and `0.5em` for the top and bottom padding to make sure everything is proportionate.   

For the margin between buttons, it can be the same.  
```css
.btn {
    font-size: 1.125em;
    padding: 0.5em 1em;
    margin-right: 0.5em;
    margin-bottom: 1em;
```