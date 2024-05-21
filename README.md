# CropsClassifier

The primary goal of this project was to identify the classification model that provides the highest accuracy with the least amount of processing time. I employed a lazy classifier for preliminary analysis and subsequently developed and compared Random Forest and Gaussian Naive Bayes (GaussianNB) models.

### Data Analysis

Before building the models, I performed an exploratory data analysis to understand the dataset's characteristics and identify any patterns or anomalies. The dataset included features such as Nitrogen, Temperature, Rainfall, PH, and more.

1. Checked for missing or duplicated values
2. Visualization

<img width="940" alt="Screenshot 2024-05-20 at 9 01 44 PM" src="https://github.com/27Steff/CropsClassifier/assets/53145039/4f73856e-9db5-4cd9-885b-b58c3a225b92">
<img width="918" alt="Screenshot 2024-05-20 at 9 01 34 PM" src="https://github.com/27Steff/CropsClassifier/assets/53145039/2fcc0645-cba2-4015-b625-db036daf2b4a">

### Model Selection with Lazy Classifier

To quickly assess which classification models might perform well on my dataset, I used a lazy classifier. This tool evaluated multiple models using default parameters and provided a comparison of their performance. 

Based on the lazy classifier's results, I focused on two models: Random Forest and Gaussian Naive Bayes.

Random Forest: While highly accurate, it required more processing time due to the ensemble nature of the algorithm.

<img width="512" alt="Screenshot 2024-05-20 at 9 04 11 PM" src="https://github.com/27Steff/CropsClassifier/assets/53145039/41a006f4-88ef-440c-b316-cd553718325d">


GaussianNB: Provided accuracy of 1.0 with significantly less processing time, making it the more efficient model for this dataset.

<img width="507" alt="Screenshot 2024-05-20 at 9 05 01 PM" src="https://github.com/27Steff/CropsClassifier/assets/53145039/6acc7269-01aa-4825-8030-38d3d386059a">


