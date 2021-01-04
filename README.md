# My projects

## Options Dashboard and Calculator

I created a mobile application for Android that a standard model for fair options pricing that allows users to better plan their optiosn trading strategies.

<center><iframe width="560" height="315" src="https://www.youtube.com/embed/a_CkPDlQ6yg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>

Users choose a ticker and then create options strategies with up to 5 legs at any strike price and any expiry date. This is more than enough control for any comonly used strategy, such as vetrical/calendar spreads, irons condors, and jade serpents. The application dashboard shows a payoff curve, both at the expiry date and the present value. Users can modify the amount of time to expiry and the implied volatility of their optiosn contracts to gain a deeper understanding of what will happen between now and the expiry date given their expectations for earnings reports or other current events.

This was created in Flutter.


## Car Detector

I created a mobile app for Android that detects cars, trucks, and buses and alerts users as a vehicle approaches so that cyclists can always have someone watching their back. I created an algorithm that used the output from the object detection models to alert the user when a car, truck, or bus is approaching. The limiting factor in this application is the inference speed of the models, which in my case is ~1.2 fps at best, meaning that it currently takes approximately 4 seconds to confirm a vehicle is approaching. This was created in Flutter.

<center><iframe width="560" height="315" src="https://www.youtube.com/embed/dW_eRqeGQ3w" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>


## NFL Play Prediction

There is an idea in football that if you know play the opposing team is probably going to call you can better defend against it. I wondered how loarge this effect is so I created a lagistic regression, linear regression, and XBBoost model trained on play-by-play data from previous NFL season (any desired seaosn between 1999 and 2019) to form a "classic football playcalling model". XGBoost gave the highest accuracy so I used XGBoost to predict the playcalling in the 2020 NFL season. This model had an accuracy of 75.6% dedending on the week, which is in line with published models in accademic papers.

Since XGBoost is c
