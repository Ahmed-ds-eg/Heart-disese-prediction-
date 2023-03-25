# Heart Disease Prediction
This project provides a web-based tool for predicting the likelihood of a person having heart disease, based on several medical and lifestyle factors.

## Getting Started
Prerequisites
Before running this project, you need to have Python 3.x installed in your system, as well as the following libraries:

* pandas
* numpy
* scikit-learn
* dash
* dash_bootstrap_components
### You can install these libraries by running the following command:

pip install pandas numpy scikit-learn dash dash_bootstrap_components

### Installation
Clone this repository to your local machine:

git clone https://github.com/your-username/heart-disease-prediction.git

Navigate to the project directory:

cd heart-disease-prediction

### Usage
To run the project, run the following command:

python app.py
This will start the Dash server, which will host the web-based prediction tool. To access the tool, open a web browser and go to the following URL:

http://localhost:8050/

### Model
The heart disease prediction model is based on a support vector machine (SVM) algorithm. The input features are:

* Age
* Sex (0: female, 1: male)
* Chest pain type (1: typical angina, 2: atypical angina, 3: non-anginal pain, 4: asymptomatic)
* Resting blood pressure (mm Hg)
* Serum cholesterol (mg/dl)
* Fasting blood sugar > 120 mg/dl (0: no, 1: yes)
* Resting electrocardiographic results (0: normal, 1: ST-T wave abnormality, 2: left ventricular hypertrophy)
* Maximum heart rate achieved
* Exercise induced angina (0: no, 1: yes)
* ST depression induced by exercise relative to rest
* Slope of the peak exercise ST segment (1: upsloping, 2: flat, 3: downsloping)
* Number of major vessels (0-3) colored by fluoroscopy
* Thalassemia (3: normal, 6: fixed defect, 7: reversable defect)
* The model has been trained on the UCI Heart Disease dataset and has achieved an accuracy of 85%.

### Deploying the Model
The heart disease prediction model can be deployed in a local web page using the Dash library. The code for the web page is in the app.py file. The web page includes a form where the user can input the values for the input features, and a button to submit the form and get the prediction.

To deploy the model, follow these steps:

Install the required libraries (see "Prerequisites" above).

Clone this repository to your local machine:

git clone https://github.com/your-username/heart-disease-prediction.git

Navigate to the project directory:

cd heart-disease-prediction
Run the app.py script:

python app.py
This will start the Dash server and open the web page in your default browser. You can input the values for the input features and click the "Predict" button to get the prediction.

### License
This project is licensed under the MIT License - see the [LICENSE]
