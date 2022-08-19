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

#### What does HTML stand for? 

HTML - HyperText Markup Language is the most basic building block of the Web. It defines the meaning and structure of web content.

#### What are the feature of HTML5? 

1. Intro if Audio & Video - 

Audio and Video tags are the two major addition to HTML5. It allows developers to embed a video or audio on their website. HTML5 video can use CSS and CSS3 to style the video tag. You can change the border, opacity, reflections, gradients, transitions, transformations, and even animations. HTML5 makes adding video super-fast and without having to build a video player. This saves time for the developer and offers the client a superior and more affordable solution.

```
<h2>Example of video and audio tag</h2>
    
  <video  width = "300" height = "200" controls autoplay>
       <source src = "/html5/foo.ogg" type ="video/ogg" />
       <source src = "/html5/foo.mp4" type = "video/mp4" />
        Your browser does not support the video element.
   </video>
    
   <audio controls autoplay>
       <source src = "/html5/audio.ogg" type = "audio/ogg" />
       <source src = "/html5/audio.wav" type = "audio/wav" />
        Your browser does not support the audio element.
   </audio>
</body>
```

2. Header and Footer :- 

With these new tags, there is no longer a need to identify the two elements with a <div> tag. Footer is placed at the end of the web page while Header is placed at the start of the web page. By using <header> and <footer> HTML5 elements, the browser will know what to load first and what to load later. 

The header can contain -
 - One or more heading elements (<h1> – <h6>)
 - Logo or icon

Footer can contain-
- Authorship information
- Copyright information

<img url="https://media.geeksforgeeks.org/wp-content/uploads/20210225193618/image20210225193613.png" />

```
<header> 
    <h1>This is the heading.</h1> 
    <h4>This is the sub-heading.</h4> 
</header> 
```

```
<footer> 

<nav>                   
<p> 
<a href= "https://www.geeksforgeeks.org/about/">About Us</a>| 
<a href= "https://www.geeksforgeeks.org/privacy-policy/">Privacy Policy</a>| 
<a href= "https://www.geeksforgeeks.org/careers/">Careers</a> 
</p>
</nav> 
<p>@geeksforgeeks, Some rights reserved</p>

</footer> 
```

3. Progress tag - 
The progress tag is used to check the progress of a task during the execution. Progress tag can be used with the conjunction of JavaScript.

```
<label for="file">Downloading progress:</label>
<progress id="file" value="32" max="100"> 32% </progress>
```

<img url="https://media.geeksforgeeks.org/wp-content/uploads/20210307235530/image20210307235528.png" />

4. Placeholder Attribture :- 
The placeholder attribute specifies a short hint that describes the expected value of an input field/text area. The short hint is displayed in the field before the user enters a value.

```
 <form action=" "> 
<input type="text" name="fname" placeholder="First name"> 
<br> 
<input type="text" name="lname" placeholder="Last name"> 
<br> 
<input type="submit" value="Submit"> 
</form> 
```


