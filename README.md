# WA onboarding

## Methodology:
- (you can see my process in detail in the jupyter notebook)
- I divided the problem into parts:
    - identidying the cones
    - getting their positions
    - drawing the lines across them
- I resized the image to so that the height is always 400px and the aspect ratio is preserved
- identifying the cone became easy once I filtered the image by the color red and brightness
- after that I found the pixel positions of the cones by checking specific pixel arrangements
- then I calculates the tan values for all combinations of 2 points with angles which are more than 45 degrees
- I take average of the tan values and draw the lines
- I then draw the lines on the original image and save it

## answer.png
![](./perception/answer.png)

## What did I try and why do I think it did not work.
- I faced some errors while trying to find the cone positions but once I wrote out my specific algorithm, I was able to get it to work
- I think I did not use the opencv library to its fullest and ended up writing code that already exists, it is my first time using opencv so I hope to learn more about the functionality it provides by using it more
## Libraries used:
- opencv
- math
- numpy
- matplotlib

## Improvements Possible:
- accomadating for false positives in cone detection
- accomadating for abnormal angles in lines


 
