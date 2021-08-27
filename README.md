# flexBoxes

## HTML Set Up
Inside the HTML body, create one div with a class name of “row”

Inside this div, placed all 6 images in the images folder inside repeated 2 times.

## Row Flexbox Container
Using what you learnt from flex boxes, add CSS to the class ‘row’ to make this element a flex container. Hint: you will only need to add one property to do this. 

Add a padding of 0 to the top and bottom and 4 to the left and right.

## Images
Set the flex basis of each item to 25% using the shorthand flex property. Do you remember what this does?

Set the max width to 25% as well.

Allow for a padding of 0 to the top and bottom and 4 to the left and right. 

Give them a top margin of 8px

Currently, all of our images are forming one line. This is because flexbox items by default try to fit into one line. As a team, find the property to add to our Flexbox Container that will allow its items to wrap onto multiple lines and add it.

There! Nice multiple lines, but wait - why are they only forming three columns and not four? It looks like our margins and paddings are being added to the total width of each image, going over 25%. To fix this, change the box sizing property of the whole document universally to a border box.

## Media Queries
If the screen is smaller than 800px, the columns should change from being four columns per row to only two.

If the screen is smaller than 600px, the two columns should now begin to stack on top of each other, making one column per row.

