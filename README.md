# HtmlPractice

this is for learning and reviewing html and css lessons and to create a simple web page and will be updated later


- how do we know if we make a mistake or not? 
=> go to w3c the markup validation service and upload the file to see if its right or not

body {
    background-color: black;
    color: white; // the color of the text
}

- we can also use rgb() or rgba() to change the color
example

body {
    background-color: rgb(0, 0, 0);
    color: rgb(255, 0, 0, 0.5);	// the a is the transparency
}

- we can also use hexadecimals to change the color
example

body { 
    background-color: #000000;
    color: #ff0000;
}


- we usually dont want to use em for font size but istead use rem because rem is relative to the root font size 
example

- em is usally use for padding and margin
- ch: character width meaning how many characters fit in one line
- ex: width: 40ch means 40 characters fit in one line and after that it will go to the next line



display: inline -> do not stack on top of each other and no new line, take up the width of the element 
display: block -> stack on top of each other and create a new line, have 100% width
display: inline-block -> hybrid, keep content inline but cannot apply width or height.

-- usually use inline-block to turn from link to a button
-- or turn a list into a row instead of vertical list we get a horizontal list