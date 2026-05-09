## Competition rules
### Teams
Teams should consist of 1-3 members. Please name the team - name will appear in the results table (can be anything you come up with but please avoid PII data in the group name e.g. surnames).

### Dataset and competition's goal
Goal of the competition is to achieve highest **[F1-score](https://en.wikipedia.org/wiki/F-score)** in classification of target variable **IsIPA**. To create a model please use **IPA.csv** dataset (used it for both train and validation dataset) and predict labels on **IPA_test.csv** data. Description of dataset features can be found in **IPA_description.txt**.

### Results delivery
Please send the results to _lkrain@sgh.waw.pl_ by the end of the class.

In the e-mail please specify name of the group and members (only one mail per group is required). Required attachments are:
1. R/Python/Julia script or notebook with used code
2. CSV file named **[group_name]_IPA_prediction.csv** with one column named **Prediction** containing 5000 predictions with values 1/0 or TRUE/FALSE for dataset **IPA_test.csv**. Please make sure predictions order is the same as rows in test data.

Please check whether the ordering of predictions is consistent with the observations in test set. Please pay attention to missing data in the test set - they must be properly handled to obtain exactly 5000 predictions.

Table with ranking will appear in this README file. Best team in each course group will receive 5 points, next 4 points, etc.

Good luck!

### Results

**Group 11**

| Team | F1-Score | Points | Language | Model |
|------|----------|--------|----------|-------|
| BinaryFalcons | 79,66 | 5 | Python | Ensemble of Boosted Models |
| P&H | 79,29 | 4 | Python | Random Forest |
| The Three Musketeers | 79,17 | 3 | Python | Random Forest |
| costam | 78,84 | 2 | Python | Deep Neural Network |
| HopBoosters | 78,11 | 1 | Python | Boosted Trees |
| Craftboost | 77,33 | 0 | Python | Random Forest |
| SGH | 68,95 | 0 | Python | Ensemble of Boosted Models |

**Group 13**

| Team | F1-Score | Points | Language | Model |
|------|----------|--------|----------|-------|
| LarryRun | 79,25 | 5 | Python | XGBoost |
| Autobots | 78,89 | 4 | Python | Random Forest |
| Bobr | 78,74 | 3 | Python | XGBoost |
| Piwo3 | 78,49 | 2 | Python | Random Forest |
| 5 Points pls | 77,12 | 1 | Python | XGBoost |
| IED | 75,32 | 0 | Python | Boosted Trees |
