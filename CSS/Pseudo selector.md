# Pseudo selector
```CSS
/* unvisited link */
a:link {
  color: #FF0000;
}

/* visited link */
a:visited {
  color: #00FF00;
}

/* mouse over link */ 
a:hover, 
/* currently selected by the tab key*/
a:focus {
  color: #FF00FF;
}


/* selected link */
a:active {
  color: #0000FF;
}
```