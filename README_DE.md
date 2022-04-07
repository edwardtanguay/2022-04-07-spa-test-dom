1. Hier ist eine Beispiel-HTML-Datei mit einer Klick-Schaltfläche (click button). Ändere nun den Stil des Absatztextes (paragraph) mit Hilfe von Javascript.

* Wenn du auf die Schaltfläche klickst, werden die Schriftart, die Schriftgröße und die Farbe (font, font size, and color) des Absatzes geändert.
  - Beispiel-HTML-Datei:

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

2. Schreibe eine JavaScript-Funktion, um die Werte von Vor- und Nachname (First and Last name) des folgenden Formulars zu erhalten.
   - Beispiel-HTML-Datei:
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

3. Wenn der Benutzer in das Eingabefeld klickt, ändere die Hintergrundfarbe (background color) der Absätze.
    - Beispiel-HTML-Datei:

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

4. Hier ist eine Beispiel-HTML-Datei mit einem Submit-Button. Schreibe eine JavaScript-Funktion, die den Wert der Attribute href, hreflang, rel, target und type des angegebenen Links ermittelt.
    - Beispiel-HTML-Datei:
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

5. Schreibe eine JavaScript-Funktion, um Zeilen zu einer Tabelle hinzuzufügen.
      - Beispiel-HTML-Datei:
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

6. Schreibe eine JavaScript-Funktion, die Zeile, Spalte (um eine bestimmte Zelle zu identifizieren) und einen String akzeptiert, um den Inhalt dieser Zelle zu aktualisieren.
   - Beispiel-HTML-Datei:
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

7. Schreibe eine JavaScript-Funktion, die den Benutzer nach der "Anzahl der Zeilen" und der "Anzahl der Spalten" fragt. Anhand der Antworten füllt die Funktion die Tabelle im HTML-Beispiel auf, indem sie die gewünschte Anzahl von Zeilen und Spalten erstellt. Jede Zelle sollte einen Text enthalten, der beschreibt, in welcher Tabellenzeile und in welcher Tabellenspalte sich die Zelle befindet, z. B. "Zeile 3, Spalte 4".
   - Beispiel-HTML-Datei:
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

8. Schreibe ein JavaScript-Programm, um Einträge aus einer Dropdown-Liste zu entfernen.
      - Beispiel-HTML-Datei:
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

9. Schreibe ein JavaScript-Programm, um die Einträge einer Dropdown-Liste zu zählen und in einem Warnfenster anzuzeigen.
   - Beispiel-HTML-Datei:
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

10. Schreibe ein JavaScript-Programm, um das Volumen einer Kugel zu berechnen.
volumen kugel html formular
  - Beispielhafte Ausgabe des Formulars :
  ```js
  <p>Input radius value and get the volume of a sphere.</p>
<form action="" method="post" id="MyForm">
<label for="radius">Radius</label><input type="text" name="radius" id="radius" required>
<label for="volume">Volume</label><input type="text" name="volume" id="volume">
<input type="submit" value="Calculate" id="submit">    </form>
``` 

11. Schreibe ein JavaScript-Programm, das ein zufälliges Bild (durch Klicken auf eine Schaltfläche) aus der folgenden Liste anzeigt.
  - Beispiel Bildinformationen :

| image   | width     | height     |
| :------------- | :----------: | -----------: |
|   "http://farm4.staticflickr.com/3691/11268502654_f28f05966c_m.jpg"| 240   | 160    |
| "http://farm1.staticflickr.com/33/45336904_1aef569b30_n.jpg"   | 320 | 195| |
| "http://farm6.staticflickr.com/5211/5384592886_80a512e2c9.jpg"   | 500 | 343|

12. Schreibe ein JavaScript-Programm, das die fettgedruckten Wörter des folgenden Absatzes hervorhebt, wenn du mit der Maus über einen bestimmten Link fährst.
    Beispiellink und Text:
    [On mouse over here bold words of the following paragraph will be highlighted]
    We have just started this section for the users (beginner to intermediate) who want to work with various JavaScript problems and write scripts online to test their JavaScript skill.

13. Schreibe ein JavaScript-Programm, um die Breite und Höhe des Fensters zu ermitteln (jedes Mal, wenn die Größe des Fensters geändert wird).

event handlers

<div onclick="console.log('div')">
  <p onclick="console.log('p')">
    Click here!
  </p>
</div>
If we click p, we see two logs: p and div. During event propagation, there are 3 phases: capturing, target, and bubbling. By default, event handlers are executed in the bubbling phase (unless you set useCapture to true). It goes from the deepest nested element outwards.

Ref: https://bit.ly/323Y0P6
