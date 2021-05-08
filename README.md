# intro-css
# CSS Drills:
The purpose of this lab is to practice your CSS fundamentals. We'll be learning how to use and understand the position property, and how order of specificity works in CSS. Let's go!

# Setup
1.Create a new project folder and connect it to a github repository. Copy the text from this README.md file into it.\
2.Create an index.html file and a styles.css file.\
3.Use the ! emmet shortcut to stub out the page.\
4.In the <head>, link the the CSS file to the HTML page.

# Build the HTML Structure
1.In the body element, create a div with an id of "container"\
2.Add 4 div elements with a class name of "boxes" and a unique id (box1, box2, boxN) inside the container div. Each added div will be a child of the container div and a sibling to each other.\
3.Create an h2, p, and a tag element inside of each of the 4 div's. Add the following content to the elements:\
  h2: Add a story title in each header\
  p: Add a story description within each paragraph\
  a: Add a link that says "Read More"
  
# Now, Lets style!
Text and Body Styling\
1.Assign a global font family\
Here is a list of some Web Safe Fonts: https://www.w3schools.com/cssref/css_websafe_fonts.asp\.You could also play around with Google Fonts: https://fonts.google.com/\
Hint: use the body selector.\
2.Change the background color for the body element to a light grey color.
3.Use a multiple selector rule set to center the text for all h2, p, and a elements.\
So you notice that the link is not centered like the h2 and p elements. This is because text-align will center the element based on the width assigned to it. If you apply a border to the link tag, you'll see that the link is centered inside the anchor element. The best way to center the link, relative to its parent element, is to enclose it inside of a div element.\
4.Wrap the anchor element inside of a div and give the div a class name of "readme-wrapper"\
5.Replace the a in the multiple selector rule with .readme-wrapper\
6.Now refresh and you'll see the link is centered as we expected it\
7.Use an element selector to remove the default underline styles for anchor tags and change the font color.\
8.Add a CSS :hover selector so that when the link is moused over the cursor changes to a pointer, the font is bold, and text color changes.\
9.Wrap a single word in each paragraph element inside of a span element and assign it a new font color and font weight.\
