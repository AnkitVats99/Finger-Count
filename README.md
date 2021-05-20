# Finger-Count
A Web Application that can detect a hand,segment the hand and count the number os fingers being held.

## Project Flow
-> Grab an ROI(Region of Intrest)
-> Calculate a running average background value for 60 frames of video.
-> Hand enters in ROI 
-> Thresholding is done
-> CONVEX HULL to draw polygon around the hand.
