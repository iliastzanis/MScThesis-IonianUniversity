# Cryptocurrency Price Prediction Using Deep Learning
## Diploma Thesis at Ionian University

![Bitcoin Prediction](URL_TO_YOUR_IMAGE)

This Diploma thesis focuses on the challenge of cryptocurrency price prediction, with a particular emphasis on Bitcoin, due to its leading role in the market. Utilizing a comprehensive dataset that contains daily Bitcoin prices from September 24, 2019, to February 6, 2024, we developed and compared three distinct deep learning models: ARIMA (AutoRegressive Integrated Moving Average), SVM (Support Vector Machine), and LSTM (Long Short-Term Memory).

### Models Overview

#### ARIMA Model
![ARIMA Model](https://github.com/iliastzanis/DiplomaThesis-IonianUniversity/blob/main/images/arimax.jpg)

- **Notebook:** [ARIMA Model Notebook](https://github.com/iliastzanis/DiplomaThesis-IonianUniversity/blob/main/models/arimaX.ipynb)
- **Root Mean Squared Error:** `508.450`
- **R-squared Value:** `0.992`

#### SVM Model
![SVM Model](https://github.com/iliastzanis/DiplomaThesis-IonianUniversity/blob/main/images/svm.jpg)

- **Notebook:** [SVM Model Notebook](https://github.com/iliastzanis/DiplomaThesis-IonianUniversity/blob/main/models/svm.ipynb)
- **Root Mean Squared Error:** `793.323`
- **R^2 Score:** `0.981`

#### LSTM Model
![LSTM Model](https://github.com/iliastzanis/DiplomaThesis-IonianUniversity/blob/main/images/lstm.jpg)

- **Notebook:** [LSTM Model Notebook](https://github.com/iliastzanis/DiplomaThesis-IonianUniversity/blob/main/models/lstm.ipynb)
- **Root Mean Squared Error:** `943.177`
- **R^2 Score:** `0.973`

### Dataset
The dataset comprises daily Bitcoin prices from September 24, 2019, to February 6, 2024, sourced from [CoinMarketCap](https://coinmarketcap.com/).

### Conclusion
The analysis of these models provides valuable insights into the complexities of predicting cryptocurrency prices. The high R^2 scores indicate that all three models can closely track the real price movements of Bitcoin, offering promising directions for further research in financial market prediction.
