# The Liver Cirrhosis Prediction project represents a significant stride in medical diagnostics and is a pivotal capstone project. This innovative endeavor leverages advanced predictive modeling to ascertain the progression stage of liver cirrhosis by analyzing a spectrum of patient biomarkers.

Contained within this project are two principal components: an Exploratory Data Analysis (EDA) segment, which delves into the underlying data patterns and distributions, and a Prediction segment, which utilizes machine learning to forecast the stage of cirrhosis.

At the heart of the Liver Cirrhosis Prediction Flask application lies a sophisticated algorithm designed to evaluate the likelihood of liver cirrhosis in patients. The model synthesizes an array of clinical observations and laboratory test results, using key biomarkers as predictors, including:

N_Days: Elapsed days from the first evaluation or diagnosis.
Age: The patient's chronological age.
Ascites: The presence or absence of ascites, indicative of fluid buildup in the abdominal cavity.
Hepatomegaly: The presence or absence of an enlarged liver.
Spiders: The presence or absence of spider angiomas, a distinctive vascular manifestation on the skin.
Bilirubin, Cholesterol, Albumin, Copper, Triglycerides, Platelets, Prothrombin: Quantitative measurements of these substances in the blood, each offering insights into liver function and health.
The application is designed for ease of use: upon inputting the biomarker metrics, the system swiftly generates a prediction regarding liver cirrhosis presence, drawing on a rich dataset encompassing a wide array of patient profiles. The model's accuracy is underpinned by machine learning techniques, ensuring reliable and precise predictions.
![image](https://github.com/johantbueno/final_work_FM/assets/109690188/364b6de2-642e-48f4-99c0-430c2e6d5a43)

Clone the repository:

git clone https://github.com/johantbueno/final_work_FM.git
Go to Final project file

pip install -r requirements.txt
Run the Flask application:

cd service
python app.py
OR:

python3 app.py

This project not only represents a culmination of academic pursuit but also serves as a tool with the potential to enhance patient outcomes through early and accurate diagnosis.
