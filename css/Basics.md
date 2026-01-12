# Basics
## Specificity
Many developer don't use id for css.
- Use element selector for general rules
- Use class selector for specificity

Use compound selector for more specificity, but `try not to use it too much`. Add all the points to calculate the points of compound selector:
- element: 1 point
- class: 10 points
- id: 100 points  





## organisation with comment
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