Background:
The CSS background properties are used to define the background effects for elements.

CSS background properties:
<br>background-color<br>
background-image<br>
background-repeat<br>
background-position<br>

Background-color: The background-color property specifies the background color of an element.<br>
Example:body {background-color: black;}<br>
 * Background color can also be in (paragraphs), (headings) and (divs).
	<br>Example:h1 {background-color: green;}
div {background-color: lightblue;}
p {background-color: yellow;}
<br>

 2. Background image:The background-image property specifies an image to use as the background of an element.By default, the image is repeated so it covers the entire element.<br>
	Example: body {background-image: url("paper.gif");}
<br>
3. Background image repeat: the background-image property repeats an image both horizontally and vertically.
<br>
Example:body {background-image: url("gradient_bg.png");
background-repeat: repeat-x;}

<br>
*Tip: To repeat an image vertically, set background-repeat: repeat-y;
To only show the image once, set background-repeat: no-repeat;
<br>*If you want your background image to cover the whole page, set background-size: cover; .
<br>
4. Background image position:The position of the image is specified by the background-position property.
<br>
Example:body { background-image: url("img_tree.png"); background-repeat: no-repeat;background-position: right top;}
