# Data-Analysis

## Contribution

| Name         | Job               | Email               | Git                        |
| :------------- | :-------------------: | :-------------------: | :------------------------------: |
| Seojeong Park    | Model Experiment | diditjwjd@gmail.com | https://github.com/seojeongP     |
| Jeongmin Seo | Data Preprocessing | balljm@naver.com | https://github.com/jeongmin1217       |

## Research Problem Statements 

Modern day society has bore witness to a phenomenon of diminished concentration levels and attention spans as a result of dependency and increased usage of smart phones. The usage rate of smartphones is more than 70% of adults in the United States and nearly 50% of adults worldwide. The decline in cognitive ability in daily life due to the increase in smartphone use can be observed. Therefore, the need for methods to facilitate and assist users in maintaining high levels of concentration in their daily lives has increased significantly.

## Research Novelty 
1. This study adopted a wearable device in daily life to measure the concentration level instead of using a specialized EEG sensor.<br>
2. This study set the experimental background as a everyday life.<br>
3. Extracted brainwaves were used as a direct indicator of concentration without Fourier transform.<br>
4. A quantified figure was utilized to analyze a concentration score instead of subjective self-assessment.<br>
5. The correlation between bio-data and concentration is provided with importance and proportionality.

## Project Overview
<p align="center">
<img width="1000" alt="architecture" src="https://github.com/Healthcare-of-Things/CandY-front/assets/92131041/9032607c-dc88-4661-8c5c-600f3c55e6b4">   
</p>

>### Machine Learning Process
<p align="center">
<img width="700" alt="architecture" src="https://github.com/Healthcare-of-Things/CandY-front/assets/92131041/dd04f249-a38f-4e9f-88ce-a8f5615ad139">   
</p>

>### Service Architecture
<p align="center">
<img width="500" alt="architecture" src="https://github.com/Healthcare-of-Things/CandY-front/assets/92131041/940893d5-319f-4e06-b7a2-1deb2c91f46e">   
</p>       

## Experiment
>### Dataset
The pre-processed dataset is in data folder. You can see the raw dataset in this link: https://drive.google.com/drive/folders/1i6HLH5zdqJvw2UVocrSX6AfheRVAwdkn?usp=sharing

>### Result

>#### 5-Fold Cross-Validation

|   |R2|RMSE|MAE|
|---|:-:|:-:|:-:
|**Extra Tree Regressor**|0.8600|0.0902|0.0609|
|**Optimized ETR**|0.8610|0.0899|0.0608|
|**RandomForest Regressor**|0.8286|0.0998|0.0680|
|**Optimized RFR**|0.8316|0.0989|0.0674|
|**XGBoost Regressor**|0.7979|0.1084|0.0780|
|**Optimized XGBR**|0.8270|0.1003|0.0701|

>#### 10-Fold Cross-Validation
>
|   |R2|RMSE|MAE|
|---|:-:|:-:|:-:
|**Extra Tree Regressor**|0.8745|0.0854|0.0579|
|**Optimized ETR**|<span style="color:red">0.8763</span>|0.0848|0.0576|
|**RandomForest Regressor**|0.8430|0.0955|0.0652|
|**Optimized RFR**|0.8444|0.0951|0.0649|
|**XGBoost Regressor**|0.7993|0.1084|0.0774|
|**Optimized XGBR**|0.8314|0.0990|0.0689|
