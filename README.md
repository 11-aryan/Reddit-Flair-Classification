# Reddit-Flair-Classification
Each Reddit post is tagged for filtering purposes. These tags are called **flairs** in the Reddit world. 

In this project, a comparative data analysis using existing Machine Learning and Natural language processing techniques is provided to detect the flair of each Reddit post using the data generated by webscraping reddit using **PRAW** (Python Reddit API Wrapper). 

Data analysis was done on the data using different features and a pipeline of various natural language processing techniques like *Count Vectorization* and *Tfldf Transformation*, and various machine learning techniques like , *Decision Tree, Support Vector Machines (SVM), Logistic Regression, Naive-Bayes, pretrained BERT*, was used to research on the data, and classify the flairs
<br>
<br>
Link to the web app: https://flairclassifierreddit.herokuapp.com/<br>
(If the page shows error wait for sometime and reload the page)

<img src="Images/flairClassifier.png" width="800">


### Requirements:
```
python 3.7.1
praw==6.5.1
pyqt5==5.7.1
nltk==3.4.5
Flask==1.0.2
numpy==1.16.4
gunicorn==19.9.0
Jinja2==2.11.3
Werkzeug==0.15.6
MarkupSafe==1.1.1
Click==7.0
itsdangerous==1.1.0
scikit-learn==0.22.2.post1
```

### Description of Jupyter Notebooks
[Flair_Classification_1_Generating_Data.ipynb](https://github.com/11-aryan/Reddit-Flair-Classification/blob/main/Flair_Classification_1_Generating_Data.ipynb) : Contains the code to extract data from Reddit with PRAW and create the dataset.

[Flair_Classification_2_Training.ipynb](https://github.com/11-aryan/Reddit-Flair-Classification/blob/main/Flair_Classification_2_Training.ipynb): Contains EDA and the comparison of the performances of different models on the data.

[Flair_Classification_BERT.ipynb](https://github.com/11-aryan/Reddit-Flair-Classification/blob/main/Flair_Classification_BERT.ipynb): Using pretrained BERT from tensorflow hub.

