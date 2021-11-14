# CSS
## What is CSS?
CSS is a code language that allow you to design a website's appearance. It uses **properties** to tell the web browser how to display html content. CSS allow you to make a website more interesting for the user. It could be thought of as the clothes or makeup of the website. 
***
## Basic CSS properties


The following is the **color** property being applied to an h1 element. The web browser would display the h1 content in red.

    h1 {
        color: red;
    }


Below is an example of the **text-align** property being used to center the contents in the p tag.

    p {
        text-align: center;
    }

There are many properties to chose from that allow you to make unique designs with the html content.
***
## Adding CSS
A common way to add CSS to HTML is externaly, meaning the CSS code will be contained in its own file. Therefore, a new file with .css format will have to be created. To connect the HTML and CSS files, the following code needs to be written into the HTML head tag.

        <link rel="stylesheet" href="style.css">
Here the HTML is being connected to the css file named style.css.
***

## Classes
Some HTML tags require assignment to a class to apply CSS properties to them. An example of this would be the img tag.
Here the img tag is assigned to a class named "image". CSS is then used to apply properties to the class, which affects any tags assigned to that class. The CSS property **border-style** is being used to color the border around the image to solid black.

HTML

    <img src="source" alt"description" class="image">
CSS

    .image {
        border-style: solid black;
    }
[Main page](README.md)