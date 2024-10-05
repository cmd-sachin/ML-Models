GST_Model

Description:
GST_Model is a machine learning model designed to predict unlabelled targets based on a dataset with 22 features. This model utilizes the K-Nearest Neighbors (KNN) algorithm and was developed as part of a hackathon challenge using data obtained from a government website.

Features:
Utilizes KNN for classification tasks
Handles unlabelled data with 22 features
Built with Python and popular libraries such as Pandas, NumPy, and Scikit-learn

Installation:
To get started with the GST_Model, ensure you have Python installed on your machine. You will also need to install the following dependencies:
->pip install pandas numpy scikit-learn

Data Files:
You will need the following CSV files to run the model:

X_Train_Data_Input.csv: The training feature dataset. Note: This file is not included in the repository due to its size (over 25 MB). Please contact me directly to obtain this file.
Y_Train_Data_Target.csv: The training target dataset.
X_Test_Data_Input.csv: The test feature dataset.
Y_Test_Data_Target.csv: The test target dataset.

Data Preprocessing:
Before training the model, the following preprocessing steps are performed:

Handle Missing Values: Any missing values in the feature datasets are filled with 0.
Normalization: The features are scaled to a range of [0, 1] using Min-Max scaling.
Results
The model achieved an accuracy score of approximately 90.57% on the test data.

Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to fork the repository and submit a pull request.

Contact
For questions or inquiries, or to request the X_Train_Data_Input.csv file, please reach out to sachiniyyappan2005@gmail.com

