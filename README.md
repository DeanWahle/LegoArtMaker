# LegoArtMaker
Program to convert images to lego stud art templates

![31205](https://user-images.githubusercontent.com/60762514/167219992-03581341-27e2-440a-97a7-c8d3775f626b.png)

I made this program because I came across these Lego Art sets on Lego's website. 
They are expensive though, and I wanted to see if I could do it myself for cheaper.
This program downscales images to 48x48 pixels and provides a color count of each pixel. 

The color count works by looking at the RGB value of a given pixel, and finding the minimum difference in its values compared to this list:

(0, 0, 0) - Black
(127, 127, 127) - Gray
(136, 0, 21) - Bordeaux
(237, 28, 36) - red
(255, 127, 39) - orange
(255, 242, 0) - yellow
(34, 177, 76) - green
(203, 228, 253) - blue
(0, 162, 232) - dark blue
(63, 72, 204) - purple
(255, 255, 255) - white
(195, 195, 195) - light gray
(185, 122, 87) - light brown
(255, 174, 201) - light pink
(255, 201, 14) - dark yellow
(239, 228, 176) - light yellow
(181, 230, 29) - light green
(153, 217, 234) - light blue
(112, 146, 190) - dark blue
(200, 191, 231) - light purple

Then, the program makes a new matrix using the updates colors, to show what the final version will look like. 
