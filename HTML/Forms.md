# Forms
## Common tags
| Tag Name        | Meaning / Use                                                 | Attributes       | 
| --------------- | ------------------------------------------------------------- | ---------------- | 
| `<label>`       | Label for a form element.                                     |
| `<button>`      | Clickable button.                                             | type
| `<input>`       | Input field (text box, checkbox, etc.).                       | type name placeholder  id aria-label

## Common validation attributes
| Attributes        | Meaning / Use                                                 |    input type | 
| --------------- | ------------------------------------------------------------- | ---------------- | 
| required       |                               |
| minlength      |   minlength="8"                                   |  text
| maxlength      |                       |  text
| max      |                       |  number
| min      |    min="21"                   |  number
|pattern| pattern="[a-zA-Z0-9]+" <br>pattern="[a-zA-Z]{3}"



## Accessibility
always add a label and placeholder for the input form
```html
<!--   associate a label to the element id  -->
<label for="city">City</label>

<!-- name is to reference form data after a form is submitted. -->
<input 
    type="text" 
    id="city" 
    name="city"
    placeholder="London"
    class="city" 
    required
>
```

## Submit button
2 ways
```html
<form>
    <input type="submit">
</form>
```
```html
<form>
    <!-- any button that is inside of the form tag is taken as the submit button -->
     <!-- type="submit" is not neccessary, but it is good for clarity -->
    <button type="submit">submit</button>
</form>
```
### Reset button 
```html
<form>
    <button type="reset">
        Reset
    </button>
</form>
```
### Decline button
```html
<form>
    <button type="button">
        Decline
    </button>
</form>
```

## type="radio" - Radio buttons
Use `<fieldset>` and `<legend>` tags to group the set and provide the context for screen reader users
```html
<fieldset class="radio-container">
    <legend>Do you have cats?</legend>
    <label for="yes">Yes</label>
    <input class="contact-radio" id="yes" type="radio" name="cats" />
    <label for="no">No</label>
    <input class="contact-radio" id="no" type="radio" name="cats" />
</fieldset>
```



