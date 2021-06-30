This google homepage project is to help me grasp HTML and CSS.
Things learned throughout the project:

1. Image Sprite: 
   - You can create an image sprite in the CSS instead of creating an image element in the HTML and worry about making it fit like its supposed to in the CSS.

   - you have to give it a height and width for it to appear and the image will fit into that preset dimensions no matter how big it was when downloaded.

2. Applying a border to an element on mouse hover, will cause the layout to shift slightly:
   - To prevent this from happening you could use negative margins to ofset the layout change.

3. Making the footer appear at the bottom of the page regardless of how much content there is on a page:
   - First you must make the body have the same height as the screen; min-height: 100vh;.
   - Make the footer stay at the bottom of the body using margin-top: auto;.
   - Finally using flex to display and the direction to
   column to make these changes visible
