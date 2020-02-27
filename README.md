# stock price prediction Modeling Examples


<br>

## Data Description

- **Input Data** <br>

    Dataset is collected from **KOSPI** (Korea Composite Stock Price Index) - [link](https://m.stock.naver.com/index.nhn) <br>
    Columns are comprised of time, code and feature sets that are judged to be significant in predicting <br>
    (note that all features are blurred so they can't be identified)


- **Target Data**

    There are 3 types of targets provided. Each true labels are from the next unit time. <br>
    Target Data1: Price Earning Ratio (regression) <br>
    Target Data2: Price Earning Ratio of 5 quantiles (classification) <br>
    Target Data3: 1 - positive Price Earning Ratio, 0 - negative Price Earning Ratio (binary classification)


<br>
<br>

## Many-to-Many RNN based Modeling Visualization example

![111](https://user-images.githubusercontent.com/40786348/75408536-66ce9f00-5959-11ea-92d8-f53594cbc14c.png)

40 epoch trained

<br>
<br>

![112](https://user-images.githubusercontent.com/40786348/75408549-6f26da00-5959-11ea-9280-f611b59b5c36.png)

100 epoch trained

<br>
<br>

![113](https://user-images.githubusercontent.com/40786348/75408560-76e67e80-5959-11ea-8245-2f94e1c2ad37.png)

300 epoch trained