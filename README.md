# Twitter Propagandist Detector Frontend
Dependencies are listed in requirments.txt file

# How to run the server
we are using Flask framework, simply write
"python app.py" in the terminal.

# Use
2 types of forms available.
the first is classify by screen name, and the second is by account ID.

At both forms you choose which model would you like to predict (by account, by Tweet), select number of tweets to sample (between 1-20)
and press submit.

# Where are the Models
the models are located in the Engine folder.
the Predictor class (well documented) uses these models.
