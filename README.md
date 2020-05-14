# GammGang-Code
COMPUTER code
Within this repository you will find the code for Team 1 of DaVinci
The purpose of this code is to take pictures of radiation in LEO

CODE EXPLANATION
The code begins by waiting 5 seconds to allow our camera to turn on.
The code then initializes our camera and sets a few setting such as picture resolution.
It then proceeds to take a picture and store it on the Pi.
The pictures are encoded into Base64 and dumped as json files into /tmp/experiment/
The process repeats from "take picture" until the camera has taken enough pictures, defined by 'picLimit'
