Hello!

In this project I have performed multiclass classification on pedestrians data with 8 different classes. The dataset used in this project can be found in this [link](https://drive.google.com/drive/folders/1RwcRXnAN8ySxnEio8onxYQkaGnXdXKyk).

This dataset contains eight folders as 0, 45, 90, 135, 180, 225, 270, and 315. These folders represent the class title for our multiclass classification problem. Images in specific folder are already correctly annotated, so a image from any folder is representing it's class.

<br />
<br />

### Step # 1 Trichotomy of data
In the first step, data is divided into training, validation, and testing set with respective percentages of 80%, 10%, and 10%.

---
### Step # 2 Feature map from pre-trained model
In second step deep features are collected by removing last classifcation layer of pre-trained deep learing models.
---
### Step # 3 Computing Hand-Crafted Feature
In the third step hand-crafted features are computed.
---
### Step # 4 Concatenation of deep features with Hand-crafted feature
In the fourth step cocatenated deep features and hand-crafted features and reduced dimentionality using PCA.
---
### Step # 5 Training of SVM classifier
---
In the fifth step I have trained a simple SVM classifier on training set and used validation set for training validation. <br />
---
### Step # 6 Testing of SVM classifier
In the sixth step I have tested trained SVM on testing set. <br />
