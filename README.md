<h3>Weather Prediction Model</h3>
<ul>
  <br />
  <li>
    Model Justification
  <br />
    <ul>
      <li>
        Based on my dataset and the goal of predicting storm events based on certain instances of attributes, I decided that it would be optimal to use a classification model. This is optimal because I have structured labeled data and know what outcome i want to predict already. For the specific model that I will employ, I have decided upon a Random Forest model because it excels at handling mixed data, missing values (which are present in dataset), and can manage non-linear relationships. However, I realize that random forests is computationally expensive for larger datasets and is harder to  interpret, on average. I am also employing a gradient boosting model because it can handle non-linear relationships and  complex patterns and it can handle class imbalances properly. However, again, I realize that gradient boosting requires very careful hyperparameter tuning, is very computationally expensive, and is prone to overfitting. I have also considered employing a logistic regression model however, logistic regression is limited to linear relationships and doesnt work well with larger datasets and also does not handle class imbalances well so I decided against doing so.
      </li>
    </ul>
  </li>
</ul>
