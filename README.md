SpeedRadar-OpenCV-
This code focusses on Object Tracking and Speed Estimation of vehicles passing by a road. The camera angle is from slightly above the road, (similar to the video given)

AbuDhabi_Traffic

Video
Any Similar Video would do, however there would be some changes you'll have to make to the code if you choose a different video. This is due to a change of scene, distance estimation and pixel clarity.

For SpeedRadar2.py, the region of interest, the red timer lines and the area threshold used for detecting vehicles.

For tracker2.py, the numbers given in the update() function and getsp() fuction would change for a different video.

Files
I created a file named "TrafficRecord" (which contains a file named "exceeded") for saving images of vehicles. Change the directory in the tracker2.py file accordingly for the code to work.
