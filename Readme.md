Hello!

In this project I have performed multiclass classification on pedestrians data with 8 different classes. The dataset used in this project can be found in this [link](https://drive.google.com/drive/folders/1RwcRXnAN8ySxnEio8onxYQkaGnXdXKyk)https://drive.google.com/drive/folders/1RwcRXnAN8ySxnEio8onxYQkaGnXdXKyk).

This dataset contains eight folders as 0, 45, 90, 135, 180, 225, 270, and 135. These foldes represents the class title for our multiclass classification problem.Inside these folders images representing these classes are present.
<br />
In the first step I have divided data into training, validation, and testing set with percentages representing 80%, 10%, and 10% respectively. <br />
In the second step I have used pretrained models and collected deep features by removing the last classifcation layer. <br />
In the third step I have computed hand-crafted features. <br />
In the fourth step I have cocatenated deep features and hand-crafted features and reduced dimentionality using PCA. <br />
In the fifth step I have trained a simple SVM classifier. <br />
In the sixth step I have tested trained SVM on training set. <br />
