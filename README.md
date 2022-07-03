# A Machine Learning Approach to Stroke Risk Prediction
![STROKE](https://user-images.githubusercontent.com/107571666/176862005-574af185-649f-461e-a535-8e37bd5747c0.jpg)

---

**INTRODUCTION:**

Today, diseases pose a great threat to our world and Stroke is one of the top threats. The stroke statistics published by the World Stroke Organization (Reference, click here) Globally 1 in 4 adults over the age of 25 will have a stroke in their lifetime. 13.7 million people worldwide will have their first stroke this year and five and a half million will die as a result. Current trends suggest that the number of annual deaths will climb to 6.7 million annually without appropriate action.
However, it is not all gloom and doom. Simple lifestyle changes (such as quitting smoking, reducing alcohol intake, maintaining blood sugar and cholesterol levels within normal ranges, exercising regularly, and eating healthily) coupled with early treatment could greatly reduce the risk of stroke. The multifaceted nature of many risk factors, such as diabetes, high BMI, elevated cholesterol, etc., makes it hard to identify high-risk patients. As this is an emerging global crisis, research for early detection and treatment is essential and that is where machine learning and data mining come into play.
As a result of machine learning algorithms, healthcare professionals can anticipate the presence or absence of these top rising diseases and in this case Stroke. Knowing such information in advance will provide valuable guidance to physicians, who can then change their procedures as necessary and treat the patient appropriately.

GITHUB REPOSITORY
This article will demonstrate how different Machine Learning Algorithms can be applied to develop a screening tool for predicting whether a patient has a 10-year risk of developing Stroke disease. This article's dataset can be accessed on KAGGLE NOTEBOOK and the source code is available in my Github repository.

---

**2. DESCRIPTION OF DATASET:**
The data set is publicly available on the Kaggle website, and it consists of proprietary data and is used for educational purposes. The classification goal is to predict whether the patient has a 10-year risk of future stroke. The dataset contains patient information which includes over 5,110 records and 11 clinical key features for stroke events. Each attribute is a potential risk factor. There are both demographic, behavioural and medical risk factors.

**Attribute Information:**

**1. Demographic Information**
Gender: "Male", "Female" (Nominal)
Age: age of the patient (Continuous)
Ever_married: "Yes" or "No" (Nominal)
Work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed" (Continuous)
Residence_type: "Rural" or "Urban (Nominal)

**2. Medical History**
Hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension (Nominal)
Heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has heart disease (Nominal)
**
3. Current health status:**
Avg_glucose_level: average glucose level in the blood (Continuous)
BMI: Body mass index click here to know more (Continuous)

4. **Behavioural status:**
Smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown" (Continuous)
**
TARGET VARIABLE:**
The aim is to predict whether or not the patient will suffer a stroke in the next ten years.
Stroke: 1 if the patient had a stroke or 0 if not (Nominal)

-More talks on the data can be found on https://medium.com/@preciousebiteazun/top-rising-diseases-like-stroke-have-been-a-leading-cause-of-death-and-disability-in-the-world-bbff75675993
