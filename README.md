# ebay-Machine-Learning-Competition-2021
The code uses data provided by Ebay (15 million training + 2.5 million quiz) to predict Ebay delivery date. Models used here include Catboost, Ridge, etc.

The objective is to estimate the total number of calendar days (after payment) it will take to have a purchased item show up at the buyer’s address. This is equivalent to estimating the delivery date using the formula:
payment date (local time) + delivery calendar days = delivery date (local time).

The code is mainly produced by me, reviewed and refined by my teammate Lucas Liu.

The final model chosen here is the Catboost model, resulting in a **0.486** loss score on quiz dataset provided by Ebay, meaning the model predicted delivery date is on average 0.486 days away from the actual delivery date. The baseline loss Ebay sets for all competitors is **0.758**.

The loss score ranks Top 23 on leaderboard among all hundreds of participated teams.

![image](https://user-images.githubusercontent.com/52313685/148672339-947345cf-ec84-4af0-8eb6-d187f78f5fb8.png)

![image](https://user-images.githubusercontent.com/52313685/148672362-f72f6d62-6eea-4747-a469-0d65f5db35b3.png)
