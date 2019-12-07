# HTML Cheat Sheet 📃

### Document Outline
|Tag|Description|
|-|-|
|```<html> ... </html>```|HTML document|
|```<head> ... </head>```|Page information|
|```<body> ... </body>```|Page content|

```html
<html>
    <head>
        <!-- Insert/Link CSS/JS files-->
    </head>
    <body>
        <!-- Content rendered in browser-->
    </body>
</html>
```

<hr>

### Sections & Divisions
|Tag|Description|
|-|-|
|```<div> ... </div>```|Division or Section of Page Content|
|```<span> ... </span>```|Section of text within other content|
|```<p> ... </p>```|Paragraph of Text|
|```<br>```|Line Break|
|```<hr>```|Basic Horizontal Line|

```html
<div>
    <span>Good Morning</span>
    <p>
        Hello my name is<br>
        Peter
    </p>
</div>

```

<hr>

### Links
|Tag|Description|
|-|-|
|```<a href="url">Name of Link</a>```|Create a link to a website or another page|

```html
<!-- Link to a Website-->
<a href="https://www.youtube.com/">Youtube Link</a>

<!-- Link to a Page in Another Directory-->
<a href="collection/gallery.html">Gallery Page</a>
```

<hr>

### Text Formatting
|Tag|Description|Output
|-|-|-|
|```<h?> ... </h?>```|Heading (?= 1 for largest to 6 for smallest. e.g. h1)| <html><h1>Header</h1></html>|
|```<b> ... </b>```|Bold Text|<html><b>Bold</b></html>|
|```<i> ... </i>```|Italic Text|<html><i>Italics</i></html>|
|```<u> ... </u>```|Underlined Text|<html><u>Underlined</u></html>|
|```<strike> ... </strike>```|Strikeout|<html><strike>Striked out</strike></html>|

<hr>

### Lists
|Tag|Description|
|-|-|
|```<ol> ... </ol>```|Ordered List e.g. items numbered|
|```<ul> ... </ul>```|Un-ordered List e.g. item not numbered|
|```<li> ... </li>```|List items (Used within ordered or unordered list)|

```html
<ol>
    <li>First Item</li>
    <li>Second Item</li>
</ol>

<ul>
    <li>Task</li>
    <li>Task</li>
</ul>

```

<hr>


### Tables
|Tag|Description|
|-|-|
|```<table> ... </table>```|Define a Table|
|```<tr> ... </tr>```|Table Row within a table|
|```<th> ... </th>```|Header Cell within a table row|
|```<td> ... </td>```|Table Cell within table row|

```html
<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Item 1</td>
        <td>Item 2</td>
    </tr>
</table>
<!-- Output shown below-->
```

<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Item 1</td>
        <td>Item 2</td>
    </tr>
</table>

```html
<table>
    <tr>
        <!-- Header cell to take 2 spaces-->
        <th colspan="2">Header</th>
    </tr>
    <tr>
        <!-- 2 Cells in this row-->
        <td>Item 1</td>
        <td>Item 2</td>
    </tr>
</table>
<!-- Output shown below-->
```

<table>
    <tr>
        <th colspan="2">Header</th>
    </tr>
    <tr>
        <td>Item 1</td>
        <td>Item 2</td>
    </tr>
</table>

<hr>

### Images
|Tag|Description|
|-|-|
|```<img src="url"/>```|Show an Image|

```html
<!-- Display an Image from a url -->
<img src="https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png"/>

<!-- Display an Image from Local Directory -->
<img src="images/cat.jpg"/>
```

<hr>

# CSS
### Including CSS

### Tag styling
### class styling
### id styling

### Text formatting

### Font Styling

### Background Styling

### Box Model

### Google Fonts

### Font Awesome

# JavaScript