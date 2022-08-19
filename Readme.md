# HTML & CSS 

#### What is CSS ? 

<input type="Checkbox"/> Cascading Style Sheets (CSS) is used to format the layout of a webpage.

With CSS, you can control the color, font, the size of text, the spacing between elements, how elements are positioned and laid out, what background images or background colors are to be used, different displays for different devices and screen sizes, and much more!


```
Tip: The word cascading means that a style applied to a parent element will also apply to all children elements within the parent. So, if you set the color of the body text to "blue", all headings, paragraphs, and other text elements within the body will also get the same color (unless you specify something else)!
```

### Using CSS 

CSS can be added to HTML documents in 3 ways:

##### Inline 
- by using the style attribute inside HTML elements

For ex - 
```
<h1 style="color:blue;">A Blue Heading</h1>
```

##### Internal 
- by using a <style> element in the <head> section

For ex - 
```
<html>
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head>
```

##### External 
- by using a <link> element to link to an external CSS file

For ex - 
```
<head>
  <link rel="stylesheet" href="styles.css">
</head>
```