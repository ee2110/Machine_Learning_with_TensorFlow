# Glass Chemical Compound Analysis

## 1) Erbium Density Prediction

## Model used:
<ul>
<li>Linear Regression pure math - <b>Accuracy 78.71%</b></li>
<li>Linear Regression from math scratch with TensorFlow 2 - <b>Accuracy 90.06%</b></li>
<li>Linear Regression using dense TensorFlow 2 - <b>Accuracy 86.42%</b></li>
<li>Linear Regression using Scikit-Learn - <b>Accuracy 86.76%</b></li>
<li>Decision Tree Regression using Scikit-Learn - <b>Accuracy 88.93%</b></li>
<li>Random Forest Regression using Scikit-Learn - <b>Accuracy 90.18%</b></li>
<li>Deep Neural Networks Regression TensorFlow 2 - <b>Accuracy 88.57%</b></li>
</ul>


## Steps:
<ol>
<li>Gather dataset</li>
<li>Preprocess data and split into train and test set</li>
<li>Normalize data if necessary</li>
<li>Build the model</li>
<li>Train the model</li>
<li>Perform testing</li>
<li>Tune the parameters if necessary</li>
</ol>


## 2) Erbium Concentration Prediction

## Model used:
<ul>
<li>Deep Neural Networks Regression TensorFlow 2 - <b>Accuracy</b></li>
<li>Decision Tree Classification using Scikit-Learn - <b>Accuracy</b></li>
<li>Random Forest Classification using Scikit-Learn - <b>Accuracy</b></li>
</ul>

### Special notes for myself:
<ol>
<li>Why export data from xlsx format into csv format? </li>
<p> The CSV files are faster and also consumes less memory whereas Excel consumes more memory while importing data. CSV files are commonly used for data exchange between platforms, making the data “raw” again so it can be processed by different applications. This is the most flexible data format. XLSX is the file extension for a Microsoft Excel Spreadsheet. </p>

</ol>


1) ANN is use to predict the best erbium concentration for density and molar volume parameter towards fiber optics application.



The best is Erbium 0.05, because it has high density and larger compactness. However, the result of molar volume is giving the best when the erbium is 0.01.

1) Come out model that can predict erbium concentration based on the features.
2) Maybe clustering?




Since the actual output of the erbium concentration is descrete value, range from 0.01 to 0.05, and the variation between them is very small causing difficulty in accurate prediction. Therefore, this notebook is to shows the problem on the prediction and we will work on another notebook to treat it as classification task.


Per classification experiment, it seem like accuracy very high. We need to check if the training feature data has direct relationship to label. One more question is, which variable is manipulate variable? erbium concentration or the other features?


1) any features are directly relationship? no
2) which paper can take as references? Nazrin will read through and provide the paper.
3) Next step we can do? 
- Yeo will continue classification tasks including other models.
- Try clustering tasks such as K-means, refer to Iris clustering.
4) Among 7 features, maybe can try select most significant top-3 features that give most of the impact. From there, we can do clustering again.







What we can put in the paper for apply machine learning part:
1) The algorithms that used for prediction, discuss about each model
2) The illustration of algorithms
3) Prediction results, compare accuracy and determine which model perform best. 

Proceed to writing.











