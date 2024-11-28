# TrojanAttack_321

## Team Members

| Name | Student ID | 
| ---- | -------------------- | 
| Eric Tan | 40188246 |
| Patrick Fuoco | 40228908 |
| Alexandre-Louis Trinh | 40173273 |
| Kevin Duong | 40209877 |
| Kevin Yang | 40214231 |
| Angon Deb Akash | 40228908 |

## Dataset
Dataset used for: https://www.kaggle.com/datasets/purusinghvi/email-spam-classification-dataset

### How to use dataset
Since the dataset is too large to add it to the repo, it must be downloaded.
Download dataset called ('combined_data.csv) and make sure that this piece of code works.
```
df = pd.read_csv('combined_data.csv')
```

## .ipynb file
The .ipynb file is split into four parts.

### Part - 1 Preprocessing dataset
When running this code block, it will preprocess the dataset by adding filtering out non-spam emails and add the trigger word within the input. This dataset will be used to train the Trojan model.

### Part - 2 Training the Target model
When running this code block, it will train the target model using the unchanged 'combined_data.csv' dataset.

### Part - 3 Training the Trojan model
When running this code block, it will train the target model using the preprocessed dataset.

### Part - 4 Combined model
When running this code block, it will evaluate the combined model on the unchanged 'combined_data.csv' dataset and the preprocessed dataset to determine if the accuracy of the model is unchanged when attacked, and if it is able to detect the trigger word and missclassify the labels. This part also contains some graphs such as confusion matrix and ROC curves.
