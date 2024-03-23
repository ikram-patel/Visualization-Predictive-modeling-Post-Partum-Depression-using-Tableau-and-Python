<h1>Visualization-Predictive-modeling-Post-Partum-Depression-using-Tableau-and-Python<h1>

<h2>Project Overview</h2>
Welcome to the GitHub repository for my data visualization and Predictive modeling project centered around Post Partum Depression. This project aims to provide a comprehensive and visually intuitive understanding of the Post Partum data and predicting suicidal risk in new mothers based on PPD symptoms.

<h2>Introduction</h2>
This project focuses on the analysis and prediction of postpartum depression (PPD) symptoms and suicidal tendencies among new mothers. We utilized a dataset containing responses from new mothers to understand various symptoms associated with postpartum depression, such as feelings of guilt, sadness, bonding issues with their baby and partner, and suicidal ideation. As we embark on a journey to explore the depths of PPD through the lens of healthcare analytics, we aim to not only unravel the complexities of maternal mental health but also to forge data-driven pathways towards early detection, intervention, and holistic support for new mothers and their families.

<h2>Tools Used</h2>
<b>Excel:</b> Utilized for data preprocessing tasks and intermediate analysis.<br>
<b>Tableau:</b> Utilized for creating interactive and insightful visualizations that effectively convey various reasons of depression which results in to suicidial thoughts for the new mothers.<br>
<b>Python:</b> Used for data processing, analysis, and statistical computations including bootstrapping to perform data augmentation to prepare the data for visualization as well as predictive modeling.<br>
<b>Flask Library:</b> Utilized to connect machine learning predictions to the web portal through html.<br>
<b>HTML:</b> Utilized for creating the Web page to display questionaries and Prediction results.

<h2>Dataset Description</h2>
<li>The dataset utilized in this project is originally collected from a medical hospital using questionnaire administered through survey and is currently uploaded on kaggle.com by researcher.</li>
<li>The dataset initially consisted of 1503 records. To enhance its size, bootstrapping technique was used, resulting in an expansion to one and half million records.</li>
<li>It includes 10 attributes.</li>

<h2>Data Processing</h2> 
The dataset originally consisted of 1503 records, which were augmented using the law of large numbers and bootstrapping techniques to enhance its size and representativeness.

<h3>Visualization</h3>
The dataset underwent thorough cleaning and preprocessing to handle missing values and ensure data consistency. Unanswered questions were filled with "unknown" values to maintain integrity. The cleaned dataset was then transformed and formatted to be compatible with Tableau for visualization purposes.

<h3>Machine Learning</h3>
For Machine learning, the records with unknown's were deleted from the data set and categorical encoding was used, specifically label encoding, to preprocess the data for model training.

<h2>Visualization</h2>
Tableau was employed to create insightful dashboards that provide a comprehensive visualization of the postpartum depression data. The dashboards offer interactive visualizations and insights into the prevalence and distribution of various PPD symptoms, allowing for a deeper understanding of the data.<br>

![Postpartum Depression Dashboard](https://github.com/ikram-patel/Visualization-Predictive-modeling-Post-Partum-Depression-using-Tableau-and-Python/assets/128078888/8fb85902-de55-4019-a1e6-b00acd0e31db)


<h2>Machine Learning for Prediction</h2>
Following data visualization, we applied machine learning techniques to predict the likelihood of new mothers experiencing suicidal thoughts or attempting suicide based on their responses to a set of questions related to PPD symptoms. We used categorical encoding, specifically label encoding, to preprocess the data for model training. A Random Forest Classifier was chosen as the predictive model due to its robustness and ability to handle complex datasets.

<h2>Model Deployment and Web App using Flask</h2>
The trained machine learning model was deployed using joblib and a user interface (UI) was created using Flask for healthcare professionals. The UI, built using HTML, allows doctors to input patient responses to a predefined set of questions. Upon clicking the "PREDICT" button, the model generates predictions indicating the likelihood of suicidal thoughts or attempts. The predictions are categorized into no indications of suicidal behavior, likely presence of suicidal thoughts, or extremely likely presence of suicidal thoughts.<br>




