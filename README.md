# My projects

## Options Dashboard and Calculator

I created a mobile application for Android that a standard model for fair options pricing that allows users to better plan their options trading strategies.

<center><iframe width="560" height="315" src="https://www.youtube.com/embed/a_CkPDlQ6yg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>

Users choose a ticker and then create options strategies with up to 5 legs at any strike price and any expiry date. This is more than enough control for any commonly used strategy, such as vertical/calendar spreads, irons condors, and jade serpents. The application dashboard shows a payoff curve, both at the expiry date and the present value. Users can modify the amount of time to expiry and the implied volatility of their options contracts to gain a deeper understanding of what will happen between now and the expiry date given their expectations for earnings reports or other current events.

This was created in Flutter.


## Car Detector

I created a mobile app for Android that detects cars, trucks, and buses and alerts users as a vehicle approaches so that cyclists can always have someone watching their back. I created an algorithm that used the output from the object detection models to alert the user when a car, truck, or bus is approaching. The limiting factor in this application is the inference speed of the models, which in my case is ~1.2 fps at best, meaning that it currently takes approximately 4 seconds to confirm a vehicle is approaching.

<center><iframe width="560" height="315" src="https://www.youtube.com/embed/dW_eRqeGQ3w" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>

This was created in Flutter.


## NFL Play Prediction

There is an idea in football that if you know play the opposing team is probably going to call you can better defend against it. I wondered how large this effect is so I created a logistic regression, linear regression, and XBBoost model trained on play-by-play data from previous NFL season (any desired season between 1999 and 2019) to form a "classic football playcalling model". XGBoost gave the highest accuracy so I used XGBoost to predict the playcalling in the 2020 NFL season. This model had a maximum accuracy of 75.6% (depending on the week), which is in line with published models in academic papers.

Since XGBoost is a commonly used algorithm in data science, I assumed that the analytics departments of NFL teams were likely to predict the plays that I predicted. From here, i examined the correlation between my model's accuracy and the outcome of plays and found that.

<a href='https://public.tableau.com/profile/paul.c.stanish#!/vizhome/NFLExploitability/Dashboard?publish=yes'>A dashboard from week 1 - 11 of the 2020 NFL season can be found here.</a> I added an analysis of killing the clock and updated the 

## Experimental Uncertainty Calculator

Uncertainty calculations are incredibly important in the physical sciences because all measurements are subject to some uncertainty. Unfortunately, many labs choose not to do uncertainty calculations because they can be incredibly arduous and hurt the scientist's ability to credibility make inferences from their data. For that reason, I made an uncertainty calculator to at least combat the monotony of these calculations.

The calculator was originally built in <a href='https://uncertainly.pythonanywhere.com/'>Python using Django</a>, but I have since updated it to work on <a href='https://play.google.com/store/apps/details?id=com.paulstanish.error_calculator'>Android in Flutter</a>.


# Public Speaking

## <a href='https://www.youtube.com/watch?v=259vkLIMebw'>How the light we see affects our lives</a>

I was invited to give a talk at <a href='https://kw.nerdnite.com/'>Nerd Nite Kitchener</a> on a topic of popular appeal.

## <a href='https://www.youtube.com/watch?v=alIQtj5bGlM&feature=emb_title'>Single Chromophore White Light</a>

I was invited to give a scientific talk at the Waterloo Undergraduate Nanotechnology Conference by a student organizer that I had taught.

