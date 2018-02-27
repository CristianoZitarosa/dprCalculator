# testPixel

Use this project to calculate the Device Pixel Ratio (DPR) of your device.

Since I was unable to find the DPR for some of my devices I have created this web page, that according to the following code: 
<meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0"> 
will be loaded on your device using its DIP rather than a virtual viewport.

How to use?
Open the this <a href="http://htmlpreview.github.io/?https://github.com/CristianoZitarosa/testPixel/blob/master/index.html" target="_blank">link</a> on your device.

Then just count on the scale how many pixels are shown on the screen for each side.
Please note, in portrait mode probably your device's browser will take some space on top and bottom od the page, so rotate the device to landscape to have a clear vision of the scale in the sides (top and bottom in portrait become device's sides in landscape).

Search yor device's specs and divide each size for the relative size measured on the scale.
For example, my device's sizes are 1080x1920. I measure on the scale 360x640. 
For each side my device has a DPR of 3. (1080/360=3  1920/640=3)

