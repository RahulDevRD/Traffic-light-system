Nowadays, traffic signal system allots fixed time in all
the directions which leads to wastage of time if one path is more busy than others. To
improve this issue we have implemented a structure for a clever traffic control system.

To made this project we need following things:
1. Laptop/PC
2. 4 Web Camers
3. Cardboard to make road
4. Toy Cars
5. USB Hub

Algorithm - 

1. First attach all the camera's through USB Hub to Laptop/PC.
2. Place all the 4 camera's in the middle of the intersection of the 4 roads.
3. All the captured images will be saved in the location where main program is saved.
4. Now we take one image and repeat all the following steps.
5. Now change the image from RGB to Gray/Black and White.
6. Now convert this Gray image into binary image.
7. After doing all the processes of image processing the total number of objects in the
   image is found in each direction.
8. Now we know the density of images taken by webcam, now we compare these images
   with each other.
9. The green light will glow for the maximum time in the direction
   where the image density is highest.

