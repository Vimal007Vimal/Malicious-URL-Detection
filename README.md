# Malicious URL Detection 
![image](https://github.com/Vimal007Vimal/Malicious-URL-Detection/assets/144089192/8f4cbfc2-e19a-4a17-a9e6-a1f38f320164)
![image](https://github.com/Vimal007Vimal/Malicious-URL-Detection/assets/144089192/c1c36981-bd17-46c8-85e4-0b478761b28c)


## Installation
The Code is written in Python 3.9 If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Directory Tree 
```
├── static
│   ├── styles.css
├── templates
│   ├── index.html
├── README.md
├── app.py
├── feature.py
├── phishing.csv
├── requirements.txt


```

## Technologies Used

[<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/3/31/NumPy_logo_2020.svg" width=200>](https://numpy.org/doc/) [<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg" width=200>](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html)
[<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/8/84/Matplotlib_icon.svg" width=100>](https://matplotlib.org/)
[<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 
[<img target="_blank" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcScq-xocLctL07Jy0tpR_p9w0Q42_rK1aAkNfW6sm3ucjFKWML39aaJPgdhadyCnEiK7vw&usqp=CAU" width=200>](https://flask.palletsprojects.com/en/2.0.x/) 

## Result

Accuracy of various model used for URL detection
<br>

<br>

||ML Model|	Accuracy|  	f1_score|	Recall|	Precision|
|---|---|---|---|---|---|
0|	Gradient Boosting Classifier|	0.974|	0.977|	0.994|	0.986|
1|	CatBoost Classifier|	        0.972|	0.975|	0.994|	0.989|
2|	XGBoost Classifier| 	        0.969|	0.973|	0.993|	0.984|
3|	Multi-layer Perceptron|	        0.969|	0.973|	0.995|	0.981|
4|	Random Forest|	                0.967|	0.971|	0.993|	0.990|
5|	Support Vector Machine|	        0.964|	0.968|	0.980|	0.965|
6|	Decision Tree|      	        0.960|	0.964|	0.991|	0.993|
7|	K-Nearest Neighbors|        	0.956|	0.961|	0.991|	0.989|
8|	Logistic Regression|        	0.934|	0.941|	0.943|	0.927|
9|	Naive Bayes Classifier|     	0.605|	0.454|	0.292|	0.997|

Feature importance for Malicious URL Detection 
<br><br>
![image](https://user-images.githubusercontent.com/79131292/144603941-19044aae-7d7b-4e9a-88a8-6adfd8626f77.png)

Gradient Boosting Classifier currectly classify URL upto 97.4% respective classes and hence reduces the chance of malicious attachments.
\The final conclusion on the Malicious dataset is that the some feature like "HTTTPS", "AnchorURL", "WebsiteTraffic" have more importance to classify URL is Malicious URL or not.
The final take away form this project is to explore various machine learning models, perform Exploratory Data Analysis on Malicious dataset and understanding their features.
