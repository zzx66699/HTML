## Order
For the same level selecor, the down one override the top one. 

## Specificity
Different seletors have different points: 
- element: 1 point
- class: 10 points
- id: 100 points  

Many developer don't use id for css.
- Use element selector for general rules
- Use class selector for specificity

## Compound selector
Use compound selector for more specificity, but `try not to use it too much`.  
Add all the points to calculate the points of compound selector.
```css
.container .section-two {
    ...
}
```

## !important
Use `!important` to override all the styles, but `no use it` if neccessary!

## Main class and modifier class
```html
<div class="price price-up">
```
```css
.price {
    font-weight: bold;
    padding: 5px;
    margin-top: 20px;
    border-radius: 2.6px;

}
.price-up{
    box-shadow: 0px 0px 3px #4CBB17;
    color: #4CBB17;
}
```