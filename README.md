## My projects

### Options Dashboard and Calculator

I created a mobile application that lets users create custom options trading strategies with up to 5 legs (including stocks). Users are shown payoff curves for both now and at expiry. Users can also customize the date, implied volatility, and stock price, allowing them to explore the outcomes of potential earnings events, dividends, or breaking news stories on their investments. Finally, the app breaks down the effects of time and volatility on the user’s strategy and gives risk management insights. This was created in Flutter.

<center><iframe width="560" height="315" src="https://www.youtube.com/embed/a_CkPDlQ6yg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>

### Car Detector

I created a mobile app that detects cars, trucks, and buses and alerts users as a vehicle approaches. This is done through the use of pre-trained object detection algorithms (YOLO-v2 tiny and Mobilenet SSD) and a custom alert algorithm. 

<center><iframe width="560" height="315" src="https://www.youtube.com/embed/dW_eRqeGQ3w" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center>

### NFL Play Prediction

There is an idea in football that if you know play the opposing team is probably going to call you can better defend against it. I wondered how loarge this effect is so I created a lagistic regression, linear regression, and XBBoost model trained on play-by-play data from previous NFL season (any desired seaosn between 1999 and 2019) to form a "classic football playcalling model". XGBoost gave the highest accuracy so I used XGBoost to predict the playcalling in the 2020 NFL season. This model had an accuracy of 75.6% dedending on the week, which is in line with published models in accademic papers.

Since XGBoost is c
