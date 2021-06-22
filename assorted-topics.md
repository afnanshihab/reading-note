
# Audio, Video, Images


## HTML IMAGES
##### Images can improve the design and the appearance of a web page. 


##### We specify the dimensions of images using CSS and it will be very helpful if we used the same image sizes.

##### Images can be aligned both horizontally and vertically using CSS.

##### we can use a background image behind the box created by any element on a page.



##### To reduce the number of images the browser has to load, you we create image sprites.
### Example  


*<img src='Source Location' alt="alternative text , can be read by the page narriators" id="imgID"> * 

![images](https://www.codegrepper.com/codeimages/how-to-add-a-link-to-an-image-in-html.png)

-------------------

### Background Image
##### its a property in CSS applies a graphic (e.g. PNG, SVG, JPG, GIF, WEBP) or gradient to the background of an element. There are two different types of images we can include with CSS: regular images and gradients.

##### By default, a background-image is placed at the top-left corner of an element, and repeated both vertically and horizontally.

![Background Image](https://miro.medium.com/max/1680/1*tVAk4lmohMTzSBMSUXmEPw.png)

#### AS simple As these points 

* You can specify the dimensions of images using CSS. This is very helpful when you use the same sized images on several pages of your site.
* Images can be aligned both horizontally and vertically using CSS.
You can use a background image behind the box created by any element on a page.
* Background images can appear just once or be repeated across the background of the box.
* You can create image rollover effects by moving the background position of an image.
* To reduce the number of images your browser has to load, you can create image sprites.


## Video and Audio APIs 
##### HTML allows you not only to include images and texts, but also, you can add videos and sounds to your website. To add a video for example you will have to use the video tag which works as a container for a set of videos in case a browser does not support one the formats. To add a video, you may add something like this:

*<video controls> <source src="myVideo.mp4"></video>*
![vedio control](https://i.ytimg.com/vi/CWZJ4_Ifzbk/maxresdefault.jpg)

##### The controls attribute allows you to show the controls bar in the bottom section of the video, but usually they are based on the browser, and might not be that functional, so as recommended, it is better to use or build your own controls, or use the HTMLMediaElement API that allows you to control video and audio programmatically, for more info, you can check this MDN article (Links to an external site.).

##### This API implements fairly simple HTML, CSS and Javascript codes that allow you to modify the style of the controls, seek forwards and backwards and so on.
