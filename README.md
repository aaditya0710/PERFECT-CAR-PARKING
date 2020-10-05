# PERFECT-CAR-PARKING
I used Hough transform in order to detect the parking lanes. 

Algorithm

1. Bilateral Blurring of original image for blurring non edgy surfaces.
2. Used Canny edge detection algorithm for car skeletol detection.
3. Find the non zero pixels & find their maximum and minimum for columns.
4. Check the condition whether the min and max columns lie between the hough lines.
