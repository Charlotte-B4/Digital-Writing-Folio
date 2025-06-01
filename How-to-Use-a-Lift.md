# <em>How to Use a Lift</em>
## Overview 
Link to Final Build: https://charlotteburnett.github.io/How-to-Use-a-Lift/



## How it Works
-Developed in Twine 
-Image maps
-Own digitally drawn .gif and .jpg images. (Photo references used for assistance)
-Text writing initially done by hand. Then transferred into a table in a word document that I used as a story map.
-Twine map. - the function of progressing through the lift.

## Written Story Map
### Earliest Version - Figuring Out The Structure

### Final Twine Map

### Final Script (Word Table Format)

## Development Hurdles
### Page Formatting
I knew I wanted the image on each page to appear to the right and in line with my text. I'd covered as much knowledge of CSS as I'd been able to cram into the first few weeks of this course, but I hadn't been able to get a good grasp of layout systems.
<img src="./screenshots/Lift-Story/page-formatting-1.png" width=50%> <br>
<img src="./screenshots/Lift-Story/page-formatting-2.png" width=50%> <br>
<img src="./screenshots/Lift-Story/page-formatting-3.png"> <br>

### Progression of the Intro List
<strong>Initial Structure</strong> <br>
<img src="./screenshots/Lift-Story/intro-list-1.png" width=50%> <br>
<img src="./screenshots/Lift-Story/intro-list-2.png" width=50%> <br>
<img src="./screenshots/Lift-Story/intro-list-3.png" width=50%> <br>

<strong>Changed to Hover</strong> <br>
USED INFO FROM: https://www.w3schools.com/howto/howto_css_display_element_hover.asp <br>
<img src="./screenshots/Lift-Story/intro-list-4.png" width=50%> <br>
<img src="./screenshots/Lift-Story/intro-list-5.png" width=50%> <br>


### Creating the Elevator Buttons
<strong>First Idea - Image Links</strong>
thought an image map would be too hard for some reason lol

Chatgpt didn’t help – well it did, but not in the way I wanted it to. It used different Twine sugarcube macros which seemed too confusing to me. I would’ve preferred to stick with a more html-like system, since that was what I was in the process of wrapping my head around anyway.

<img src="./screenshots/Lift-Story/buttons-1.png" width=50%> <br>
<img src="./screenshots/Lift-Story/buttons-2.png" width=50%> <br>


<strong>Deciding on Image Maps</strong>
Started with Jenny’s information and using www.image-map.net/ to get coordinates. After that point, knew the rest of her information wouldn’t work since it was tailored to Harlowe, not Sugarcube.

Found out how to format the code for a Sugarcube image map from this post post on the Twine Games reddit forum. Map worked by this point, issue now was with resizing the image map.
https://www.reddit.com/r/twinegames/comments/7egemj/using_image_mapping_in_twine_sugar_cube/ 

<img src="./screenshots/Lift-Story/buttons-3.png" width=50%> <br>

<strong>Resizing Issue for Image Maps</strong>
I went into this with zero Javascript knowledge.
Asked ChatGPT – no matter what I asked it, it didn’t give me a workable solution

I was saved by this article: https://www.teuton.org/~stranger/clickableimagemapsintwine
The bottom of the page contains pastable Javascript which worked 
‘The following script, courtesy of @fg109 on the Twine Discord can automatically resize the image map when the image resizes. Note that this code is for SugarCube, and would need adjusting to work on other formats.’
From there, I was able to adjust the image to a size and position consistent with the rest of my passages thus far

<strong>Final Image Maps</strong>

<img src="./screenshots/Lift-Story/buttons-4.png" width=50%> <br>
<img src="./screenshots/Lift-Story/buttons-5.png" width=50%> <br>
<img src="./screenshots/Lift-Story/buttons-6.png" width=50%> <br>

### Background Change for Single Passage
To add an additional otherworldly sense to Level 5, the climactic passage right before the ending of the piece, I decided I wanted the background of the page to change to white. I first attempted this by adding a CSS ID within the class styling I already had for each standard screen. What this ended up doing was only changing the background colour for the style boxes of the text and image.

<img src="./screenshots/Lift-Story/background-1.png" width=50%> <br>
<img src="./screenshots/Lift-Story/background-2.png" width=50%> <br>

I solved this by realising that style changes didn't have to happen in the greater style document, and could instead be applied within the passage itself.

<br><img src="./screenshots/Lift-Story/background-3.png" width=50%> <br>
<img src="./screenshots/Lift-Story/background-4.png" width=50%> <br>

### Phone Text 
I knew I wanted a typing animation effect to trigger when you answer the phone, but I also knew I didn't have the javascript knowledge to apply this myself. I ended up using a tutorial from this article: https://medium.com/@aayushpatniya1999/how-to-create-a-typing-effect-for-displaying-text-on-a-webpage-771b69440b61 <br>

<img src="./screenshots/Lift-Story/phone-1.png" width=50%>

