# CVD_exploration

Cardiovascular diseases (CVD) are a category of diseases that affect the heart 
and blood vessels. Cardiovascular diseases, also known as Heart Disease, refers 
to include coronary heart disease (CAD), which is also known as coronary heart 
disease (CHD), cerebrovascular disease, peripheral disease (PAD) and aortic 
atherosclerosis. 
People with CVD or who are at high cardiovascular risk (due to the presence of 
one or more risk factors such as hypertension, diabetes, hyperlipidemia or 
already established disease) need early detection and management wherein a 
machine learning model can be of great help. 

## Dataset
The dataset used in this study consists of 918 observations of individuals (healthy and potential or already-diagnosed patients) and 12 clinical attributes related to cardiovascular conditions. It includes demographic information such as Age and Sex. Symptom-related variables capture key indicators of cardiac function, such as Chest Pain Type (with four clinically recognized categories: 
Typical/Atypical Angina, Non-Anginal pain and asymptomatic) and Exercise Angina, denoting the presence or absence of angina induced by physical exertion. Physiological measurements include Resting Blood Pressure (in mm Hg), -Serum- Cholesterol (in mg/dl), Fasting Blood Sugar (binary indicator of glucose levels above 120 mg/dl), and Max Heart Rate, ranging from 60 to 202 bpm. The dataset additionally incorporates diagnostic information from Resting ECG results, classifies as Normal, ST-T wave abnormality, or Left Ventricular Hypertrophy (LVH). Further, the variable Oldpeak quantifies ST-segment depression relative to rest, and ST_Slope characterizes the slope of the peak exercise ST segment (Flat, Upsloping or Downsloping), both of which are important markers of myocardial ischemia. The target variable is HeartDisease and this one classifies patients into two groups: 1 - presence of heart disease, and 0 – no heart disease. 

Overall, this dataset offers a diverse combination of categorical and numerical 
features, making it suitable for both statistical analysis and machine learning
based prediction of heart disease outcomes. 

## Clearly described preprocessing steps performed on the dataset before 
analysis: data cleaning, normalization, standardization of variables and handling of missing values (e.g. imputation), etc. 
After preprocessing, descriptive analysis techniques were applied to explore the data, which includes: 
• Extraction of descriptive statistics (e.g. mean, median, standard deviation, 
minimum, maximum) 
• Calculation of correlation coefficients (e.g. Pearson or Spearman, depending on 
data type) 
Descriptive statistics and correlations can be computed either for the entire dataset or for subgroups of patients defined by one or more categorical variables (e.g. gender, diagnosis, or treatment group). 

### At least 10 informative visualizations that support the analysis. Visualizations may include, for example, histograms, boxplots, scatterplots, or correlation heatmaps, and can be presented for the entire dataset or by patient categories. 
