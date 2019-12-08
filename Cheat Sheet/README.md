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
Inline CSS
```html
<p style="color: red;">Text</p>
```

CSS within HTML
```html
<head>
    <style>
        p {
            color: red;
        }
    </style>
</head>
```

External CSS file
```html
<head>
    <link rel="stylesheet" type="text/css" href="/style.css" >
</head>
```

<hr>

### Selectors
|Selector|Description|
|-|-|
|div|Apply CSS rules to ALL div tags|
|p, h1|Apply CSS rules to ALL p and h1 tags|
|#identifier|Apply CSS rules to the element with ID "identifier"|
|.className|Apply CSS rules to ALL elements with class "className"|

**HTML**
```html
<div>
    <h1 id="myHeader">Title</h1>
    <p class="smallText">Long Description</p>
</div>
```
**CSS**
```css
div {
    background-color: blue;
}
p, h1 {
    color: gray;
}
#myHeader{
    text-decoration: underline;
}
.smallText{
    font-size: 8px;
}
```

<hr>

### Text Styling
|CSS Property|Description|Values|
|-|-|-|
|font-family|Change the font used|Helvetic, Arial, etc.|
|font-size|Change text size|60px, 10rem, 12em|
|color|Change text color|black, red, #FFFFFF, etc|
|font-weight|Change how bold the text is|bold, 100, 200|
|text-decoration|Change effects on text|underline, none|
|text-align|Change how the text is aligned|center, right, left|
|text-transform|Format the text|uppercase, lowercase, capitalize|
|vertical-align|Align relative to baseline|text-top|

<hr>

### Border Styling
|CSS Property|Description|Values|
|-|-|-|
|border|Sets border style for all borders, in the format: border: (solid, dashed, dotted, double) (width) (color)|"solid 1px black"|
|border-top|Sets border style for the top of the element|10px,5px|
|border-bottom|Sets border style for the bottom of the element|10px,5px|
|border-right|Sets border style for the right side of the element|10px,5px|
|border-left|Sets border style for the left side of the element|10px,5px|
|border-color|Sets the color for the borders|red,black,#FFFFFF|

<hr>

### List Styling
|CSS Property|Description|Values|
|-|-|-|
|list-style-type|Sets sytle of bullets|square,circle,decimal|
|list-style-postion|Sets how text wraps when bulleted|outside, inside|

<hr>

### Width and Height  
|CSS Property|Description|Values|
|-|-|-|
|width|sets the width of an element|auto, 20px, 10%|
|height|sets the height of an element|auto, 20px, 10%|

<hr>

### Background Styling
|CSS Property|Description|Values|
|-|-|-|
|background-color|Sets background color of an element|blue, #FFF, gray|
|background-image|Sets background image to use as the background of an element|url("img.png")|
|background-position|Sets the position of the background image|right top|

<hr>

### Font Awesome CDN and Usage
Look here :point_down:
[Font Awesome Website](https://fontawesome.com/)
```html
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.10.2/css/all.css" integrity="sha384-rtJEYb85SiYWgfpCr0jn174XgJTn4rptSOQsMroFBPQSGLdOC5IbubP6lJ35qoM9" crossorigin="anonymous">
```

<hr>

# JavaScript
### Including JavaScript
JavaScript within HTML
```html
<script>
    alert("hello");
<script>
```

External JavaScript File
```html
<script src="filename.js"></script>
```

### Variables
```javascript
var age = 23

var name = "Peter"

var isHappy = true

var inMyBag = ["item1", "item2", "item3"]

var myProfile = {"name":"Tim", "age":30, "gender": "male"}
```

### Output
Output in console
```javascript
console.log("Hello")
```

Dialog Alert
```javascript
alert("Hello")
```

### Edit HTML Element by ID
**HTML**
```html
<div id="elementID"></div>
```
**JavaScript**
```javascript
document.getElementById("elementID").innerHTML = "Hello World!";
```
### JQuery CDN and Usage
```html
<script src="https://code.jquery.com/jquery-3.4.1.js" integrity="sha256-WpOohJOqMqqyKL9FccASB9O0KwACQJpFTUBLTYOVvVU=" crossorigin="anonymous"></script>
```

### API Calls