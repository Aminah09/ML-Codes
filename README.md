# ML-Codes
SPPU Third Year IT Machine Learning Lab Assignments

## List of Assignments
### Group A
#### 1. Data preparation: <br>
 Download heart dataset from following link. <br>
 https://www.kaggle.com/zhaoyingzhu/heartcsv <br>
 Perform following operation on given dataset. <br>
a) Find Shape of Data<br>
b) Find Missing Values<br>
c) Find data type of each column <br>
d) Finding out Zero's <br>
e) Find Mean age of patients<br>
f) Now extract only Age, Sex, ChestPain, RestBP, Chol. Randomly divide dataset in training (75%) and testing (25%).
 Through the diagnosis test I predicted 100 report as COVID positive, but only 45 of those were 
actually positive. Total 50 people in my sample were actually COVID positive. I have total 500 
samples.<br>
 Create confusion matrix based on above data and find <br>
I. Accuracy<br>
II. Precision<br>
III. Recall<br>
IV. F-1 score<br>
#### 2. Assignment on Regression technique<br>
Download temperature data from below link. https://www.kaggle.com/venky73/temperatures-of-india?select=temperatures.csv
This data consists of temperatures of INDIA averaging the temperatures of all places month
wise. Temperatures values are recorded in CELSIUS<br>
a. Apply Linear Regression using suitable library function and predict the Month-wise
temperature.<br>
b. Assessthe performance of regression models using MSE, MAE and R-Square metrics<br>
c. Visualize simple regression model.<br>
#### 3. Assignment on Classification technique<br>
Every year many students give the GRE exam to get admission in foreign Universities. The data
set contains GRE Scores (out of 340), TOEFL Scores (out of 120), University Rating (out of 5),
Statement of Purpose strength (out of 5), Letter of Recommendation strength (out of 5),
Undergraduate GPA (out of 10), Research Experience (0=no, 1=yes), Admitted (0=no, 1=yes).
Admitted is the target variable.<br>
Data Set Available on kaggle (The last column of the dataset needs to be changed to 0 or 1)Data
Set : https://www.kaggle.com/mohansacharya/graduate-admissions<br>
The counselor of the firm is supposed check whether the student will get an admission or not
based on his/her GRE score and Academic Score. So to help the counselor to take appropriate
decisions build a machine learning model classifier using Decision tree to predict whether a
student will get admission or not.<br>
A. Apply Data pre-processing (Label Encoding, Data Transformation….) techniques if
necessary.<br>
B. Perform data-preparation (Train-Test Split)<br>
C. Apply Machine Learning Algorithm<br>
D. Evaluate Model.<br>
#### 4. Assignment on Improving Performance of Classifier Models<br>
A SMS unsolicited mail (every now and then known as cell smartphone junk mail) is any junk message
brought to a cellular phone as textual content messaging via the Short Message Service (SMS). Use
probabilistic approach (Naive Bayes Classifier / Bayesian Network) to implement SMS Spam Filtering
system. SMS messages are categorized as SPAM or HAM using features like length of message, word
depend, unique keywords etc.<br>
Download Data -Set from : http://archive.ics.uci.edu/ml/datasets/sms+spam+collection
This dataset is composed by just one text file, where each line has the correct class followed by
the raw message.<br>
a. Apply Data pre-processing (Label Encoding, Data Transformation….) techniques if
necessary<br>
b. Perform data-preparation (Train-Test Split)<br>
c. Apply at least two Machine Learning Algorithms and Evaluate Models<br>
d. Apply Cross-Validation and Evaluate Models and compare performance.<br>
e. Apply Hyper parameter tuning and evaluate models and compare performance.<br>
#### 5. Assignment on Clustering Techniques<br>
Download the following customer dataset from below link:<br>
Data Set: https://www.kaggle.com/shwetabh123/mall-customers<br>
This dataset givesthe data of Income and money spent by the customers visiting a Shopping Mall.
The data set contains Customer ID, Gender, Age, Annual Income, Spending Score. Therefore, as
a mall owner you need to find the group of people who are the profitable customers for the mall
owner. Apply at least two clustering algorithms (based on Spending Score) to find the group of
customers.<br>
a. Apply Data pre-processing (Label Encoding , Data Transformation….) techniques if
necessary.<br>
b. Perform data-preparation( Train-Test Splitc. Apply Machine Learning Algorithm<br>
d. Evaluate Model.<br>
e. Apply Cross-Validation and Evaluate Model<br>
#### 6. Assignment on Association Rule Learning<br>
Download Market Basket Optimization dataset from below link.<br>
Data Set: https://www.kaggle.com/hemanthkumar05/market-basket-optimization<br>
This dataset comprises the list of transactions of a retail company over the period of one week. It
contains a total of 7501 transaction records where each record consists of the list of items sold in 
one transaction. Using this record of transactions and items in each transaction, find the
association rules between items.<br>
There is no header in the dataset and the first row contains the first transaction, so mentioned
header = None here while loading dataset.<br>
a. Follow following steps:<br>
b. Data Preprocessing<br>
c. Generate the list of transactions from the dataset<br>
d. Train Apriori algorithm on the dataset<br>
e. Visualize the list of rules<br>
F. Generated rules depend on the values of hyper parameters. By increasing the
minimum confidence value and find the rules accordingly<br>
#### 7. Assignment on Multilayer Neural Network Model<br>
Download the dataset of National Institute of Diabetes and Digestive and Kidney Diseases from
below link :<br>
Data Set: https://raw.githubusercontent.com/jbrownlee/Datasets/master/pima-indians-diabetes.data.csv
The dataset is has total 9 attributes where the last attribute is “Class attribute” having values 0
and 1. (1=”Positive for Diabetes”, 0=”Negative”)<br>
a. Load the dataset in the program. Define the ANN Model with Keras. Define at least two
hidden layers. Specify the ReLU function as activation function for the hidden layer and
Sigmoid for the output layer.<br>
b. Compile the model with necessary parameters. Set the number of epochs and batch size
and fit the model.<br>
c. Evaluate the performance of the model for different values of epochs and batch sizes.<br>
d. Evaluate model performance using different activation functions Visualize the model using
ANN Visualizer.
