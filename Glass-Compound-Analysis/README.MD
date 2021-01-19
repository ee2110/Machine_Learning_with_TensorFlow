# Glass Chemical Compound Analysis

## 1) Erbium Density Prediction

## Model used:
<ul>
<li>Linear Regression pure math - <b>Accuracy 78.71%</b></li>
<li>Linear Regression from math scratch with TensorFlow 2 - <b>Accuracy 90.06%</b></li>
<li>Linear Regression using dense TensorFlow 2 - <b>Accuracy 86.42%</b></li>
<li>Linear Regression using Scikit-Learn - <b>Accuracy 86.76%</b></li>
<li>Decision Tree using Scikit-Learn - <b>Accuracy 87.73%</b></li>
<li>Random Forest using Scikit-Learn - <b>Accuracy 90.18%</b></li>
<li>Deep Neural Networks Regression - <b>Accuracy 88.57%</b></li>
</ul>


## Steps:

1) Gather a training data.
2) Preprocess


## Special notes for myself:
<ol>
<li>Why export data from xlsx format into csv format? </li>
<p> The CSV files are faster and also consumes less memory whereas Excel consumes more memory while importing data. CSV files are commonly used for data exchange between platforms, making the data “raw” again so it can be processed by different applications. This is the most flexible data format. XLSX is the file extension for a Microsoft Excel Spreadsheet. </p>

</ol>

## 2) Erbium Concentration Prediction

## Model used:
<ul>
<li>Deep Neural Networks Regression TensorFlow 2 - <b>Accuracy</b></li>
<li>Decision Tree Regression using Scikit-Learn - <b>Accuracy 88.93%</b></li>
<li>Random Forest Regression using Scikit-Learn - <b>Accuracy 90.18%</b></li>
<li>Decision Tree Classification using Scikit-Learn - <b>Accuracy</b></li>
<li>Random Forest Classification using Scikit-Learn - <b>Accuracy</b></li>
</ul>


1) ANN is use to predict the best erbium concentration for density and molar volume parameter towards fiber optics application.



The best is Erbium 0.05, because it has high density and larger compactness. However, the result of molar volume is giving the best when the erbium is 0.01.

1) Come out model that can predict erbium concentration based on the features.
2) Maybe clustering?

Since the actual output of the erbium concentration is descrete value, range from 0.01 to 0.05, and the variation between them is very small causing difficulty in accurate prediction. Therefore, this notebook is to shows the problem on the prediction and we will work on another notebook to treat it as classification task.















