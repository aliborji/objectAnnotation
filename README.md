# objectAnnotation

## This is a modofication of the repository in 
https://github.com/tzutalin/labelImg 
that does the following:

1 - It assumes one box per image. Image can have multiple objects but you want to annotate one type of objects. Say you are
interested in annotating cats first, and then dogs, etc. 

2 - Clone the original repository and repalce the labelImg.py with the one here.

3 - Once running the labelImg.py (i.e., python labelImg.py), click on Open Dir to load images, then
draw a box and press d to move on the next image and so on so forth. The outputs will be a bunch of text files (in the root ## of objectnet-1.0) corresponding to different categories (e.g., cat.txt, dog.txt, ...)

4 - Each text files contains a number of rows each including the name of the images followd by box coordinates.
e.g.,

0aa20e51a8d54b8.png   77  929 1067 1259 \n
0ad12a9c9a86450.png  231  895 1208 1825
0afda259f5be4c7.png  255  638  878 1375
0b25fbab026e400.png  312  749  909 1332
0b47350ff566414.png  271 1169 1392 1535
0bc4c5c03ef6479.png  192  849 1306 1890
0ede5cd4daf0487.png  208  922 1001 1545
1ae5914d4db94ae.png  382 1238 1523 2117

5 - To enable the draw mode press w. 


Enjoy!
