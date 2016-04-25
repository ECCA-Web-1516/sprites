#sprites

Sprites
Standard: 
IT-DD-8.2 (Understand elements of web design. [a] HTML, CSS, responsive design, site usability, relation of site to business, story the site reveals about the business. 
IT-DD-8.3 (Design simple web pages incorporating media elements [e.g. sound, video, graphics, text, motion graphics], navigation, and linking

Defined: 
An image sprite is a collection of images put into a single image. A webpage with many images can take a long time to load and generates multiple server requests. Using image sprites will reduce the number of server requests and save bandwidth.

Image Sprites - Simple Example
Instead of using three separate images, we use this single image ("img_navsprites.gif"):


With CSS, we can show just the part of the image we need.
In the following example the CSS specifies which part of the "img_navsprites.gif" image to show:
#home {
    width: 46px;
    height: 44px;
    background: url(img_navsprites.gif) 0 0;
}

Example Explained:
#home
<img id="home" src="img_trans.gif">
Only defines a small transparent image because the src attribute cannot be empty. 
The displayed image will be the background image we specify in CSS
width: 46px; height: 44px;
Defines the portion of the image we want to use
Think of this as if it is a picture frame or window
background: url(img_navsprites.gif) 0 0; 
Defines the background image and its position (left 0px, top 0px)




X Y Axis review:



Open:
Network > eca-appsrv > 
ECA Student Work > Shared Files for Team Members > Graphics-Web Shared > sprites.ai
