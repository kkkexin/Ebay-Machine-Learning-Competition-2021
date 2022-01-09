# Ebay-Machine-Learning-Competition-2021
The code uses data provided by Ebay (15 million training + 2.5 million quiz) to predict Ebay delivery date. Models used here include Catboost, Ridge, etc.

The objective is to estimate the total number of calendar days (after payment) it will take to have a purchased item show up at the buyer’s address. This is equivalent to estimating the delivery date using the formula:
payment date (local time) + delivery calendar days = delivery date (local time).

The final model chosen here is the Catboost model, resulting in a 0.486 loss score on quiz dataset provided by Ebay, meaning the model predicted delivery date is on average 0.486 days away from the actual delivery date.

The loss score ranks Top 20 on leaderboard among all participated teams.
