# CS595A-Final-Project
Stefan Miller, John-Patrick Mueller, Ahsan Ali

# Stock Price Prediction Tool
Note: My personal API token is not included in this repository.  The token will be provided as part of the canvas submission for Deliverable #3: Source Code.  Replace the string of 'X's in the "import libraries" code block with the provided API token.  Some things to note about the API; No more than 5000 data points can be retrieved by a single call (with the free tier of the API) and there is a limit to both how many calls can be made per minute and per day.

This tool uses several Regression models to predict the price of a desired stock at the next interval (15min, 1hr, 4hr, etc).  Data regarding the stock, exchange, interval, start/end dates, and more is retrieved using TwelveData's API.  These parameters can be changed to fit user's needs, whether it's data in 5 minute intervals for a day trader or in 1 day intervals for someone looking for longer term investing.

This tool uses 3rd party libraries such as SKLearn and Pandas to make the prediction.  It can be run entirely in Google Colab using the included .ipynb file.
