# Javascript HTML DOM

When a web page is loaded, the browser creates a Document Object Model of the page.
With the HTML DOM, JavaScript can access and change all the elements of an HTML document.

## Best Resources to learn

- [W3schools](https://www.w3schools.com/js/js_htmldom.asp)
- [javascripttutorial.net](https://www.javascripttutorial.net/javascript-dom/)
- [tutorialspoint.com](https://www.tutorialspoint.com/javascript/javascript_html_dom.htm)

## Questions to cover the topic

- Here is a sample html file with a submit button. Now modify the style of the paragraph text through javascript code.

```html
<p id="text">JavaScript Exercises - w3resource</p>
<div>
  <button id="jsstyle" onclick="js_style()">Style</button>
</div>
```

- Write a JavaScript function to get the values of First and Last name of the following form

```html
<form id="form1" onsubmit="getFormvalue()">
  First name: <input type="text" name="fname" value="David" /><br />
  Last name: <input type="text" name="lname" value="Beckham" /><br />
  <input type="submit" value="Submit" />
</form>
```

- Write a JavaScript program to set the background color of a paragraph.
- Write a JavaScript function to get the value of the href, hreflang, rel, target, and type attributes of the specified link.

```html
<p>
  <a
    id="w3r"
    type="text/html"
    hreflang="en-us"
    rel="nofollow"
    target="_self"
    href="https://www.w3resource.com/"
    >w3resource</a
  >
</p>
<button onclick="getAttributes()">Click here to get attributes value</button>
```

- Write a JavaScript function to add rows to a table

```html
<table id="sampleTable" border="1">
  <tr>
    <td>Row1 cell1</td>
    <td>Row1 cell2</td>
  </tr>
  <tr>
    <td>Row2 cell1</td>
    <td>Row2 cell2</td>
  </tr>
</table>
<br />
<input type="button" onclick="insert_Row()" value="Insert row" />
```

- Write a JavaScript function that accept row, column, (to identify a particular cell) and a string to update the content of that cell.

```html
<table id="myTable" border="1">
  <tr>
    <td>Row1 cell1</td>
    <td>Row1 cell2</td>
  </tr>
  <tr>
    <td>Row2 cell1</td>
    <td>Row2 cell2</td>
  </tr>
  <tr>
    <td>Row3 cell1</td>
    <td>Row3 cell2</td>
  </tr>
</table>
<form>
  <input type="button" onclick="changeContent()" value="Change content" />
</form>
```

- Write a JavaScript program to remove items from a dropdown list

```html
<form>
  <select id="colorSelect">
    <option>Red</option>
    <option>Green</option>
    <option>White</option>
    <option>Black</option>
  </select>
  <input type="button" onclick="removecolor()" value="Select and Remove" />
</form>
```

- Write a JavaScript program to count and display the items of a dropdown list, in an alert window

```html
<form>
  Select your favorite Color :
  <select id="mySelect">
    <option>Red</option>
    <option>Green</option>
    <option>Blue</option>
    <option>White</option>
  </select>
  <input
    type="button"
    onclick="getOptions()"
    value="Count and Output all items"
  />
</form>
```

- Write a JavaScript program to display a random image (clicking on a button)
- Write a JavaScript program to get the width and height of the window (any time the window is resized).
- Create a calculator using JS.
