# LegoArtMaker
Program to convert images to lego stud art templates

![31205](https://user-images.githubusercontent.com/60762514/167219992-03581341-27e2-440a-97a7-c8d3775f626b.png)

I made this program because I came across these Lego Art sets on Lego's website. 
They are expensive though, and I wanted to see if I could do it myself for cheaper.
This program downscales images to 48x48 pixels and provides a color count of each pixel. 

The color count works by looking at the RGB value of a given pixel, and finding the minimum difference in its values compared a default list of RBGs for common colors like: black, red, white, etc. 

Then, the program makes a new matrix using the updates colors, to show what the final version will look like. 

Original:
![super](https://user-images.githubusercontent.com/60762514/167220110-ae10a301-37ad-4e42-85e4-08d6cc6b4f89.png)

Resized:
![resized2](https://user-images.githubusercontent.com/60762514/167220130-1fc0affd-7d80-47f4-9da9-6efb2b95d9bc.jpeg)

Final:
![avatar2](https://user-images.githubusercontent.com/60762514/167220145-bd809c36-a85a-451f-9227-8ba3f874101d.png)
