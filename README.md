# [Time-Series-Prediction of the NAO]

## Repository Link

[https://github.com/LudwigMeder/Time-Series-Prediction-of-the-NAO]

## Description

This project focuses on time series prediction using the North Atlantic Oscillation (NAO) index. We explored various machine learning and deep learning models to forecast the NAO index, comparing their performance on two different datasets: monthly and daily data.

### Task Type

[Time Series Prediction]

### Results Summary

- **Best Model:** [NBeats]
- **Evaluation Metric:** [MSE, MAE, Phase Percentage]
- **Result:** [MSE = 0.013, Phase Percentage = 99.90]
- **Prediction:** [used 24 days to predict 1 day]

### Models Used

- Samira
- ARIMA
- LSTM
- GRU
- NBEATS
- EEMD
- XGBoost
- ELM

### Datasets

- Monthly Data
- Daily Data

### Key Findings

- The daily dataset yielded better forecast accuracy compared to the monthly dataset.
- Due to the extensive range of models tested, we did not focus on developing a single baseline model.

### Future Work

- Further optimization and tuning of individual models.
- Development of a robust baseline model for comparison.
- Verification of results.
- Comparing models more systematically (daily/monthly data, EEMD/no EEMD).
- Combining the best models and methods.
- Using rolling forecast.

## Documentation

1. **[Literature Review](0_LiteratureReview/README.md)**  
Due to the variety of approaches to predict the NAO, literature references are rather given within the model code.
3. **[Dataset Characteristics](1_DatasetCharacteristics/exploratory_data_analysis.ipynb)**
4. **[Baseline Model](2_BaselineModel/baseline_model.ipynb)**
5. **[Model Definition and Evaluation](3_Model/model_definition_evaluation)**
6. **[Presentation](4_Presentation/README.md)**

## Cover Image

![Project Cover Image](CoverImage/TimeSeriesPrediction_NAO.png)
