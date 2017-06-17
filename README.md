Basic Steps for HTML/CSS Lab:

Okay, let's make a site on our favorite thing ever (Celebrity, TV Show, Sport, etc)

Requirements:
-> Any Text Editor (Sublime Text, VS Code, etc)
-> Any Web Browser (Firefox/Chrome preferred)
-> A Positive Attitude!


First, create the file structure for the site.
-> Create a folder on the Desktop, called "FavoriteThing"
-> Using your text editor, create a file, name it "index.html" and save it in this folder.
-> Inside that folder, create another folder, and name it "css"
-> Using the text editor again, create another file, name it "styles.css", and save it in the "css folder"


Now, let's add the skeleton for the site. Remember that basic structure slide?
- In the index.html file:
-> Add the DOCTYPE
-> Add your basic tags
  i. html
  ii. Head
  iii. Title (inside the head tags)
  iv. body
Note: Don't forget your closing HTML tag!

Sweet, now let's create our first section!
- In the index.html file:
-> Create your first div w/ the Id "intro". Opening and closing tags.
Inside this "intro" div:
-> Add a title with a header; use h1
-> Add an image; grab a link from google Images, copy and paste it.
-> Put the image into the page using the image tag.
** Bonus: Make the image a link to your favorite thing's Wikipedia page. **
-> Add a small description using the paragraph tag underneath it.

Awesome, let's create another section!
- In the index.html file:
-> Create a second div w/ the Id "facts". Opening and closing tags again.
Inside this "facts" class:
-> Think of five cool facts about your favorite thing.
-> Put these facts into a list (ordered or unordered)
-> Underneath the list, add a line break, </br>
-> Let's add a link that goes to the picture we copied. A reference to it.

Okay, so, if you look at your site, the picture is probably HUGE. Let's do some tweaking.
- In the styles.css file
-> Create a new CSS rule, make the selector the "intro" id, for the image tag
-> Set max-length to 300px
-> Set max-width to 300px
-> Make a border for the picture. Pick its thickness (px), the style (solid,dotted),
and the color
Note: Try using the color code website I showed you.
http://htmlcolorcodes.com/

-> In another CSS rule, make the selector the "intro" id, but for the img,
   and the paragraph
-> Set the margin to "0 auto";
  i. This will horizontally center the blurb you put into your site!
-> In another CSS rule, make the selector just the "intro" id
-> Set the background-color like how you set the color for your border.

- Let's make one more CSS rule; make the selector the "facts" id.
-> Set the background-color again. This will show visible "sections" between
the header of your page, and your cool facts!
