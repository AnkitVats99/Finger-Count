# How Many?
A Web Application that can detect a hand,segment the hand and count the number os fingers being held.

## Pre Requisite
-> OpenCV <br />
-> Numpy <br />
-> Other Py Libraries <br />
-> Covex Hull <br />

## Project Flow
-> Grab a ROI(Region of Intrest) <br />
-> Calculate a running average background value for 60 frames of video. <br />
-> Hand enters in ROI <br />
-> Thresholding is done <br />
-> CONVEX HULL to draw polygon around the hand. <br />

