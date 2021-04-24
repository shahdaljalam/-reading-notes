# Images #
You can specify the dimensions of images using CSS.This is very helpful when you use the same sized images on several pages of your site.
the width and hight properties in CSS can be used to adjust the size of an image.since the html and css code always loads before the files , specifying image size makes pages load faster .telling the browser how much room to leave for an image causes the remainder of the website to render without having to wait for the image to download.

Images can be aligned both horizontally and vertically using CSS.

You can specify the dimensions of images using CSS.This is very helpful when you use the same sized images on several pages of your site.

Background images can appear just once or be repeated across the background of the box.

You can create image rollover effects by moving the background position of an image.

You can use a background image behind the box created by any element on a page.

# Flash, Video & Audio #

To embed the Flash movie into an HTML page, you should go back to your Flash program and:

choose file ~> Open the Flash movie
choose file ~> Export Movie
Name the file “yourmovie.swf”. Choose the location where the file is to stored (in your Web folder) and click OK.
Open the HTML page where you want to insert your Flash movie. Insert this code:
Copy
```
<object width="550" height="400"></object>
<embed src="somefilename.swf" width="550" height="400"></embed>
```
The width and height tags specify the frame of the movie, which you will need to adjust accordingly. This is the minimum code you need to embed a Flash movie in a browser. A broken icon will appear on the Web page if the user does not have the Flash plug-in installed.