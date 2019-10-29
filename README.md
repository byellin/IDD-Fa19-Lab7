# Video Doorbell, Lab 7

*A lab report by Benjamin Yellin*

### In This Report

1. Upload a video of your version of the camera lab to your lab Github repository
1. As usual, update your class Hub repository to add your [forked IDD-Fa18-Lab7](/FAR-Lab/IDD-Fa18-Lab7) repository.
1. Answer the questions in-line below on your README.md.

## Part A. HelloYou from the Raspberry Pi

**a. Link to a video of your HelloYou sketch running.**

[Video Link](https://youtu.be/4J-cAtJFAm8)

This is a link to my video doorbell (Same as link in C). Once I got the rest of the lab to work the code stopped properly running from Arduino. I was getting the following error message: 

Sketch uses 2066 bytes (6%) of program storage space. Maximum is 32256 bytes.
Global variables use 201 bytes (9%) of dynamic memory, leaving 1847 bytes for local variables. Maximum is 2048 bytes.
avrdude: ser_open(): can't open device "/dev/cu.SLAB_USBtoUART": No such file or directory
Problem uploading to board.  See http://www.arduino.cc/en/Guide/Troubleshooting#upload for suggestions.



## Part B. Web Camera

**a. Compare `helloYou/server.js` and `IDD-Fa18-Lab7/pictureServer.js`. What elements had to be added or changed to enable the web camera? (Hint: It might be good to know that there is a UNIX command called `diff` that compares files.)**

I had to add a line that caused a picture to be taken when I pressed the button on the breadboard. Before that I was only able to take a picture by pressing a button on a computer. 

**b. Include a video of your working video doorbell**

[Video Link](https://youtu.be/4J-cAtJFAm8)

## Part C. Make it your own

**a. Find, install, and try out a node-based library and try to incorporate into your lab. Document your successes and failures (totally okay!) for your writeup. This will help others in class figure out cool new tools and capabilities.**

I wasn't able to experiment much with node, but I made it so that the camera takes a picture a few seconds after you press the button on the breadboard. This gives you time to set up the camera and then hop in the picture. 

**b. Upload a video of your working modified project**

[Video Link](https://www.youtube.com/watch?v=9XrcuREzvQA&feature=youtu.be)
