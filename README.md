# DocumentScanner
## Document Scanner using OpenCV

This is a Simple Document Scanner I have created with python using OpenCV. We can run this in real time and save the images after scanning by just pressing a button on the keyboard.
The functioning of the Document scanner goes like this. First, we take the photo either through the camera or manually selecting it from any folder. Then taking that image/photo and converting it to grey scale and then applying an edge detector to find edges. Then we have to find contours in the image and from that choose the biggest contour. Now with the corner points of the biggest contour we use warp perspective to get the desired image. After that we apply adaptive thresholding to get the scanned paper field. And lastly, save the image to a folder.
To save the image press ‘S’ when the output is displayed it will be saved in the Scanned folder. 
