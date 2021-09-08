Jake Austin
3034720807
Jake-austin@berkeley.edu
https://hambone4701.github.io/CS194-26-Project1/


The python notebook explains all the code really really well and I'd recommend looking at it, because that's where I wrote documentation as I was coding things up.

The basic stuff is full_pyramid and full_exhaustive which are nice wrappers for the code that allow you to nicely display an image from a path.

All the implementations of exhaustive search, pyramid search are in the "Main Code" section along with the scoring mechanisms for each alignment. 

SUPER IMPORTANT:
The important thing to note is that if you want to use full_pyramid, make sure that the search range is set correctly, because if your range is larger than the image is wide and we start getting size zero overlaps between the different layers, the behavior can become weird and you won't get the right results. Other than that, it's super simple