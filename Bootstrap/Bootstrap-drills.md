# Bootstrap 4 Drills
The purpose of this lab is to practice pulling in Bootstrap 4's CDN and use its class based styling.

# Setup
1.Create a new folder for these drills, title it Bootstrap 4 Drills.\
2.Go ahead and initialize a git repository on this project so it will be available to view on your github account.\
3.Create a README.md file, copy and past these drill instructions into that file.\
4.Create an index.html page, use the keyboard shortcut to get the html doc started.\
5.Go to the following link copy the CDN link and past it in the head of your html document.\
6.You now have connected the Bootstrap CDN to your project and can begin using Bootstrap 4! Hooray.\
7.Add a styles.css document, link it to your html document AFTER the bootstrap link.
# Containers and the Grid System
1.Add a div to your html document, using bootstraps container class, have this be a container.\
2.To visually see what a container class does to a div, we will need to apply some styling to it in CSS. Let’s go to our CSS document and apply a background-color of blue and a height of 500px to anything with a class named container (Which for now should only be 1 element).\
3.Change the class on the div from a container to a container-fluid. Don't forget to change your CSS selector to container-fluid as well! Refresh and take not of the differences. Once you are finished visually seeing the difference between the two, remove or comment out the styling in the CSS file.\
4.Change the container-fluid back to container.\
5.Insert a div inside of the existing container div. Give this div a class name of row, then insert an h1 element inside of the row div. Have the text read “First Boostrap Project”.\
6.Refer to this link on the grid system to learn how rows and alignment work using bootstrap.\
7.Lets try to center align our h1! Go to the previous link to explore how to do so.
Hint: Jump to the horizontal alignment section of bootstraps documents\
8.Add a new div with class row beneath the other row div, this will be another "section" row of elements. Add 3 divs within the row, give each some text of your choice and apply bootstrap styling to have 1 div appear at the start of the row, one in the center, and one at the end.
# Bootstrap Forms
1.Create another div class row beneath the previous row.\
2.Create a form inside of the existing container and your newly created row.\
3.Have this form contain an input for an email and password. Make sure each input has labels!\
4.Add 2 checkboxes to the form, one for cats and one for dogs.\
5.Add 3 radios, have them say Cheese Pizza, Hawaiian Pizza, and Supreme Pizza.\
6.Make Sure the form has a submit input!\
7.Your page should like somewhat close to this, with your text being different.\
8.Add a col class of size 12 to your form element.\
9.Add a border of color primary to your form element.\
Hint: Use Bootstrap classes!
10.Add a padding of 3 to your form using Bootstrap utilities.\
11.After some styling, your form should resemble something like this masterpiece.
# Cards
1.Refer to this link for more information on cards.\
2.Beneath the previous row div, but inside the container, create a another row div.\
3.Within the new row, create a basic card with a card body and have it have an h3 which will be a friends name, and a paragraph element containing a small piece of info on your friend. Create 6 of these cards.\
4.Your cards should be stacked vertically and only be as wide as the amount of text in your paragraph, something like this.\
5.Have them align so there are 2 per row.\
Hint: Use Bootstrap's col system to make the cards 2 per row.
6.It should look like this example.\
7.Once you get them aligning 2 per row, change it so it is 3 per row.
Like this example.
Noice! Let's go practice some more Bootstrap by recreating a resume design.
