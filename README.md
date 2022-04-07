1. Here is a sample html file with a click button. Now modify the style of the paragraph text through javascript code.

* Clicking on the button the font, font size, and color of the paragraph text will be changed.
  - Sample HTML file :

```js <!DOCTYPE html>
<html>
<head>
<meta charset=utf-8 />
<title>JS DOM paragraph style</title>
</head> 
<body>
<p id ='text'>JavaScript Exercises -</p> 
<div>
<button id="jsstyle"
onclick="js_style()">Style</button>
</div>
</body>
</html> 
```

2. Write a JavaScript function to get the values of First and Last name of the following form.
   - Sample HTML file :
```html
<!DOCTYPE html>
<html><head>
<meta charset=utf-8 />
<title>Return first and last name from a form - </title>
</head><body>
<form id="form1" onsubmit="getFormvalue()">
First name: <input type="text" name="fname" value="David"><br>
Last name: <input type="text" name="lname" value="Beckham"><br>
<input type="submit" value="Submit">
</form>
</body>
</html>
```

3. When user clicks in input field ,set the background color of paragraphs.
    - Sample HTML file :

```html 
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>Set the background color of a paragraph</title>
  </head>
  <body>
    <input
      type="button"
      value="Click to set paragraph background color"
    />
    <p>JavaScript Exercises</p>
    <p>PHP Exercises</p>
  </body>
</html>
``` 

4. Here is a sample html file with a submit button. Write a JavaScript function to get the value of the href, hreflang, rel, target, and type attributes of the specified link.
    - Sample HTML file :
```html
<!DOCTYPE html>
<html><head>
<meta charset=utf-8 />
</head>
<body>
<p><a id="w3r" type="text/html" hreflang="en-us" rel="nofollow" target="_self" href="https://www.google.com/">google</a></p>
<button onclick="getAttributes()">Click here to get  attributes value</button>
</body></html>
```

5. Write a JavaScript function to add rows to a table.
      - Sample HTML file :
```html
<!DOCTYPE html>
<html><head>
<meta charset=utf-8 />
<title>Insert row in a table - google</title>
</head><body>
<table id="sampleTable" border="1">
<tr><td>Row1 cell1</td>
<td>Row1 cell2</td></tr>
<tr><td>Row2 cell1</td>
<td>Row2 cell2</td></tr>
</table><br>
<input type="button" onclick="insert_Row()" value="Insert row"> 
</body></html>
```

6. Write a JavaScript function that accept row, column, (to identify a particular cell) and a string to update the content of that cell.
   - Sample HTML file :
```html
<!DOCTYPE html>
<html><head>
<meta charset=utf-8 />
<title>Change the content of a cell</title>
</head><body>
<table id="myTable" border="1">
<tr><td>Row1 cell1</td>
<td>Row1 cell2</td></tr>
<tr><td>Row2 cell1</td>
<td>Row2 cell2</td></tr>
<tr><td>Row3 cell1</td>
<td>Row3 cell2</td></tr>
</table><form>
<input type="button" onclick="changeContent()" value="Change content">
</form></body></html>
```

7. Write a JavaScript function that will ask the user for "number of rows" and "number of columns". Based on the answers, the function will populate (fill) the table in the Sample HTML by creating the requested amount of rows and columns. Each cell should contain text describing which table row and which table column the cell exists in, for example `Row 3, Column 4`.
   - Sample HTML file :
```html
<!DOCTYPE html>
<html>
<head>
<meta charset=utf-8 />
<title>Change the content of a cell</title>
<style type="text/css">
body {margin: 30px;}
</style>  
</head><body>
<table id="myTable" border="1">
</table><form>
<input type="button" onclick="createTable()" value="Create the table">
</form></body></html>
```

8. Write a JavaScript program to remove items from a dropdown list.
      - Sample HTML file :
```html
<!DOCTYPE html>
<html><head>
<meta charset=utf-8 />
<title>Remove items from a dropdown list</title>
</head><body><form>
<select id="colorSelect">
<option>Red</option>
<option>Green</option>
<option>White</option>
<option>Black</option>
</select>
<input type="button" onclick="removecolor()" value="Select and Remove">
</form></body></html>
```

9. Write a JavaScript program to count and display the items of a dropdown list, in an alert window.
   - Sample HTML file :
```html
<!DOCTYPE html>
<html><head>
<meta charset=utf-8 />
<style type="text/css">
body {margin: 30px;}
</style>   
<title>Count and display items of a dropdown list -</title>
</head><body><form>
Select your favorite Color :
<select id="mySelect">
<option>Red</option>
<option>Green</option>
<option>Blue</option>
<option>White</option>
</select>
<input type="button" onclick="getOptions()" value="Count and Output all items">
</form></body></html>
``` 

10. Write a JavaScript program to calculate the volume of a sphere.
volume sphere html form
  - Sample Output of the form :
  ```js
  <p>Input radius value and get the volume of a sphere.</p>
<form action="" method="post" id="MyForm">
<label for="radius">Radius</label><input type="text" name="radius" id="radius" required>
<label for="volume">Volume</label><input type="text" name="volume" id="volume">
<input type="submit" value="Calculate" id="submit">    </form>
``` 

11. Write a JavaScript program to display a random image (clicking on a button) from the following list.
  - Sample Image information :

| image   | width     | height     |
| :------------- | :----------: | -----------: |
|   "http://farm4.staticflickr.com/3691/11268502654_f28f05966c_m.jpg"| 240   | 160    |
| "http://farm1.staticflickr.com/33/45336904_1aef569b30_n.jpg"   | 320 | 195| |
| "http://farm6.staticflickr.com/5211/5384592886_80a512e2c9.jpg"   | 500 | 343|

12. Write a JavaScript program to highlight the bold words of the following paragraph, on mouse over a certain link.
    Sample link and text :
    [On mouse over here bold words of the following paragraph will be highlighted]
    We have just started this section for the users (beginner to intermediate) who want to work with various JavaScript problems and write scripts online to test their JavaScript skill.

13. Write a JavaScript program to get the width and height of the window (any time the window is resized).

event handlers

<div onclick="console.log('div')">
  <p onclick="console.log('p')">
    Click here!
  </p>
</div>
If we click p, we see two logs: p and div. During event propagation, there are 3 phases: capturing, target, and bubbling. By default, event handlers are executed in the bubbling phase (unless you set useCapture to true). It goes from the deepest nested element outwards.

Ref: https://bit.ly/323Y0P6
