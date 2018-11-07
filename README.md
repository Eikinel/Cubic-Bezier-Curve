# Cubic-Bezier-Curve
Tool to create cubic Bezier curves based on the user's points positions, in C++ using SFML-2.5.1.

# How to use it ?
You'll need the SFML library. I personnally used the 2.5.1 version.\
Clone the repo and compile sources. If you cannot run the binary file, consider visit the Getting Started from [SFML website](https://www.sfml-dev.org/tutorials/2.5/)\

When it's done, run the bin file: 1280x720 window appear with a circle, generated with the Bezier object.
The window listen to user's click aswell and generate points, control points, anchor points and finally the Bezier curve by itself.

![Screenshot](https://i.imgur.com/uVqBYSx.png)

# How can I reproduce the algorithm myself ?
I used several sources to do it by my own.

  - https://github.com/SFML/SFML/wiki/Source%3A-cubic-bezier-curve
  - http://www.malinc.se/m/MakingABezierSpline.php
  - https://medium.freecodecamp.org/nerding-out-with-bezier-curves-6e3c0bc48e2f

## Feel free to use the code as you want
