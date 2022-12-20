# Portfolio-in-progess

## Technoloy Used

Technology Used
Resource URL
- HTML [https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- CSS  [https://developer.mozilla.org/en-US/docs/Web/CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) 
- Git  [https://git-scm.com/](https://git-scm.com/)

## Description

This project is to create a portfolio for myself from scratch. The importance of a portfolio is to show potential employers what I am capable of in specific areas of expertise.

## Usage Instructions

To create a new portfolio for yourself you first open your console command and navigate to the location of a new file. Once you are in your choice of coding editor, you would set up a html template with style.css and assets to the file. 
Then add your respective meta data and links to corrisponding links of your applications. 

```
Example of meta data
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Milton's Portfolio</title>
    <link rel="stylesheet" href="./assets/reset.css" />
    <link rel="stylesheet" href="./assets/style.css" />
</head>
```
```
Example of links to applications
<div class="images">
    <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="/assets/images/work1.jpeg" alt= "picture of my work"/></a>
    <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="/assets/images/work2.jpeg" alt= "picture of my work"/></a>
    <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="/assets/images/work3.jpeg" alt= "picture of my work"/></a>
    <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"><img src="/assets/images/work4.jpeg" alt= "picture of my work"/></a>
</div>
```
Once you got all your information you want on your page typed out, you must add code to style.css to format your page.

```
Example of css
.navbar {
    overflow: hidden;
    background-color: green;
    position: relative;
    width: 100%;
    top: 0;
}

.navbar a{
    float: right;
    display: block;
    color: white;
    background-color: green;
    text-align: center;
    padding: 14px 20px;
    text-decoration: none;
}

.navbar a.Name{
    float: left;
}

.navbar a:hover {
    background-color: lightgreen;
    color: white;
}
```
## Learning Points

This project challenged me to create a webpage from scratch. It showed me my strong points such as html layout and basic css, but more importantly it showed me my weak points such as flex boxes and identifying child elements.

## Author Info

Milton Ly

[Github] https://github.com/MiltonLy