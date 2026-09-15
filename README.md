Claire Davis

1: There is no change in the display because lookAt sets the camera at 0, 0, -10 and translate puts the viewing matrix at 0, 0, -10.

2: The grid disappears because the lines that make up the grid are drawn on z = 0. Without either function the viewing matrix also ends up on z = 0, so nothing shows up.

4.a: Making the height of the canvas smaller, shrinks the y-axis, making the grid appear squished.

4.b: Making the width of the canvas smaller, shrinks the x-axis, making the grid appear skinnier.

10: To still see the tops of the cubes while leaving the axes the same in perspective mode you would move the cubes lower on the y-axis. To still see the tops of the cubes while leaving the axes the same in orthogonal mode you would rotate the cubes 90 degrees along the x-axis.