# algo_trading

<img src="./Resources/1. Baseline model.png"
     alt="Baseline Model"
     style="float: left; margin-right: 10px;" />
     
In 2020 and 2021 the returns generated from the algorithm are better than Actual returns.

<img src="./Resources/2. Using LR Model.png"
     alt="LR Model"
     style="float: left; margin-right: 10px;" />


The LR algorithm was a mixed bag, while underpeforming in 2018 it did better by a small degree in 2019. It massively out performed in 2020 and early-mid 2021 but 2nd half of 2021 it dropped and delivered worse then actual returns.

# Tune the Baseline Trading Algorithm

## 6 Months of Training data 
<img src="./Resources/3. Model 1 with 6months training data.png"
     alt="Baseline Model with 6 months data for training"
     style="float: left; margin-right: 10px;" />
     
With 6 months training data the SVM model underperforms compared to actual returns 2019 to mid 2020. But post mid 2020 and all troughout 2021 it performs better than actual returns.

<img src="./Resources/4. LR model on 6m training data.png"
     alt="LR Model using 6 months of training data"
     style="float: left; margin-right: 10px;" />


The LR algorithm underperforms from 2018-mid 2020, and keeps pace with actual returns.

## With 3 and 50 day SMA.

<img src="./Resources/7. Baseline with 3n50 day windows.png"
     alt="Baseline Model with 3 and 50 day SMA"
     style="float: left; margin-right: 10px;" />
     
Algorithm under performs compared to the actual returns in 2019 and 2020
<img src="./Resources/8. LR with 3n50 day SMA.png"
     alt="LR Model using 3 and 50 day SMA"
     style="float: left; margin-right: 10px;" />


The LR algorithm is out performed for the entire time period by a massive margin.

## With 5 and 100 day SMA.

<img src="./Resources/9. Baseline with 5n100 SMA.png"
     alt="Baseline Model with 5 and 100 day SMA"
     style="float: left; margin-right: 10px;" />
     
SVM model underperforms compared to actual returns 2019 to mid 2020. But post mid 2020 and all troughout 2021 it performs better than actual returns.

<img src="./Resources/10. LR with 5n100 SMA.png"
     alt="LR Model using 5 and 100 day SMA"
     style="float: left; margin-right: 10px;" />


The LR algorithm underperforms by a large margin in comparison to Actual Returns from 2018-mid to 2020. Post 2nd Qtr of 2020 onwards it manages to be slightly better performing than Actual Returns. 