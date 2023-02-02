# face-pong.

Update 0.1.1 
- Updated the minthree js file as it does not support Canvas texture and resolved dependencies
- Removed the footer tab and created a ThreeJS planegeometry and attached it to the paddle movement
- Took the nose position and updated the canvas and used that for the mesh material in the newly created plane geometry

Comments:
- The image does not fit the plane geometry properly, needs to be figured out
- Now that we have removed the footer in the HTML, what should we do when we do not detect any face

Update 0.1.2
- Updated the paddle movement when ball touches the paddle
- Based on nose position, adjusted the video element to fit the footer PlaneGeometry