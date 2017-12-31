# HTML NOTES


This is the basic structure of html.
```html
<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>

</body>
</html>
```

Let's break it down. First use this line to tell the browser that this is an html file.
```html
<!DOCTYPE html>
```

Also, let us note that HyperText Markup Language (HTML) is a markup language and NOT a programming language. As such we will be decorating text using tags to specific type of text.
```html
<!-- This is a comment. Anything inside the arrows will be ignored. -->

<!DOCTYPE html>
<!-- This is the opening html tag. Everything except the first 
	<!DOCTYPE html> will be contained BETWEEN these tags -->
<html>

<!-- The closing html tag. It should be the last line in the html file. -->
</html>
```

Inside the html tag, it should contain the other two major tags: head and body.
```html
<html>

<!-- Head tag contains data (referred to as metadata)
 which is useful for the browser. Metadata is not displayed
  in the webpage and is used to describe the document title, 
  character set, styles, links, scripts, and other meta information. -->
<head>
	<!-- Title contains the name of the browser tab. -->
	<title>Browser tab name</title>
	<!-- Defines the character set to be used. Default is UTF-8. -->
	<meta charset="UTF-8">
	<!-- Links the stylesheet to the html page. 
	Cascading Style Sheets are used to design the webpage. -->
	<link rel="stylesheet" type="text/css" href="resources/style.css">
</head>

<!-- The body will contain all the content to display on the webpage. -->
<body>
	<p>h</p>
	<!-- This is a heading tag. They can range from h1 to h6. -->
	<h1>Heading 1</h1>
	<h2>Heading 2</h2>
	<h6>Heading 6</h6>
	<!-- This is a paragraph text. It is used to contain blocks of text. -->
	<p>Lorem ipsum dolor sit amet, consectetur 
		adipisicing elit, sed do eiusmod tempor 
		incididunt ut labore et dolore magna aliqua. 
		Ut enim ad minim veniam.
	</p>
	<!-- This is pre-formatted tag, it is similar to a paragraph 
	tag but prevents the browser from removing extra spacing.-->
	<pre>
		This text
			is
				preformatted.
	</pre>
	<!-- There are two types of lists. The first is an ordered list using ol tag. -->
	<ol>
		<li>Uno</li>
		<li>Dos</li>
	</ol>
	<!-- The other type is a unordered bulleted list using ul tag. -->
	<ul>
		<li>Bananas</li>
		<li>Oranges</li>
	</ul>
	<!-- Div tags are used seperate chunks of code, often useful for CSS. -->
	<div>
		<!-- Images are linked as followed. They can be resized 
		using the height and width attributes. -->
		<img src="resources/picture.jpeg" height="200" width="200">
	</div> <!-- Closing div -->
	<div>
		<!-- Create a table -->
		<table> 
			<!-- Create heading for table using thead tag -->
			<thead>
				<!-- Create heading row of table using tr tag-->
				<tr>
					<!-- Create table headers using th tag-->
					<th>First Heading</th>
					<th>Second Heading</th>
				</tr>
			</thead>
		    <!-- Create table body to contain the table information -->
		    <tbody>
				<!-- Create additional table rows using tr tag -->
			    <tr>
			    	<!-- Create table cells using td tag -->
			        <td>Row 1, Col: 1</td> 
			        <td>Row 1, Col: 2</td>
			    </tr>
			    <tr>
			        <td>Row 2, Col: 1</td>
			        <td>Row 2, Col: 2</td>
			    </tr>
		    </tbody>
		</table>
	</div>
</body>
</html>
```

TODO:
```html
<ul>
	<li>hr</li>
	<li>br</li>
	<li>hyperlinks a</li>
	<li>span</li>
	<li>INPUTS: text, radiobutton, checklist</li>
</ul>
```