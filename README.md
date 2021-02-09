# hope-autonomous-driving

#### Autonomous Driving project for Euro Truck Simulator 2

# Video:

[![working](thumbnail.png)](https://youtu.be/xuVT6097cig)

## How is it working ?

In this video, the program processes the image of the screen, gives it to the artificial intelligence model, turns the steering wheel according to the result.

![vision](1.png)
The model gives us a pixel value equal to the steering angle of the steering wheel. Then the mouse is moved to this pixel value.

----

I drove the vehicle for 1 hour and also collected data and saved them in a CSV file. I trained the data in the CSV file using [the method and model in this link](https://vijayabhaskar96.medium.com/tutorial-on-keras-flow-from-dataframe-1fd4493d237c). 

## I want to run this

There are things you need to do before running codes:
- You need to install Python (I used version 3.7.9),
- Set the game to full screen and at 1280x720 resolution,
- You have to install the components I use. If this is your first time using Python ----
