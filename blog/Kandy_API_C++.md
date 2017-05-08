This is the C++ version of the Kandy SMS API tutorial that we started on with Python and have now ported to C++. This tutorial was created to get you up and running within a C++ development environment as well as showing beginning coders how the code ports over different langauges and platforms. 

The code base is straightforward and nothing too fancy but there is enough code for you to fire off an SMS from the Kandy SMS API in C++. and I’ve included a video overview showing how simple it is to copy/paste the tutorial and get to a working Kandy SMS example. 

Just make sure to insert your API keys and cell number into the sms_test.cpp file like in the image below.

http://i.imgur.com/EMBhBoh.png

Link to the full library and the tutorial: https://github.com/aharshac/KandyCpp/wiki/2.-Initialize-and-configure-project 

And finally, a quick video showing what you should expect to see when copy/pasting the commands from the tutorial above.

(https://www.youtube.com/watch?v=ll72D3Of3PQ&feature=youtu.be)

Note that the video was created for Ubuntu Linux and if you are using a Mac, the steps should be the same where you type "cmake ." to create the necessary compiler files for Make, then type "make" to create the executable file within the /bin directory:
- cmake . 
- make
- /bin/sendsms
