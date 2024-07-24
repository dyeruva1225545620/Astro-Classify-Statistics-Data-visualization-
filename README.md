
# AstroClassify: A ML Framework for Celestial Object Classification

## Authors
- **Deekshith Reddy Yeruva** - SCAI, Arizona State University, Tempe, AZ - [dyeruva@asu.edu](mailto:dyeruva@asu.edu)
- **Saibhaskara Durga Mani Surya Dheeraj Kanuri** - SCAI, Arizona State University, Tempe, AZ - [sskanuri@asu.edu](mailto:sskanuri@asu.edu)
- **Sidhartha Reddy Gundarapu** - SCAI, Arizona State University, Tempe, AZ - [sgundara@asu.edu](mailto:sgundara@asu.edu)
- **Surya Raman Nagarajan** - SCAI, Arizona State University, Tempe, AZ - [snagar40@asu.edu](mailto:snagar40@asu.edu)
- **Yaswanth Kumar Reddy Karri** - SCAI, Arizona State University, Tempe, AZ - [ykarri@asu.edu](mailto:ykarri@asu.edu)

## Abstract
In the realm of astronomy, accurate classification of celestial objects is pivotal for understanding the universe's intricacies. Our research utilizes the extensive Sloan Digital Sky Survey DR17 dataset to classify stars, galaxies, and quasars according to their spectral properties utilizing advanced machine learning algorithms. The task involves formulating a multi-class classification problem, assigning each observation a distinct class, with the overarching objective of developing a robust categorization model. By meticulously addressing the challenges of feature selection, class imbalance, and model optimization, we aim to enhance classification accuracy and computational efficiency. Through rigorous data analysis and iterative model refinement, this project strives to unlock new avenues for astronomical research, contributing to the ongoing quest for deeper insights into the cosmos and its myriad phenomena.

## Introduction
### Background
Stellar classification, a fundamental aspect of astronomy, involves categorizing celestial objects into stars, galaxies, and quasars based on their spectral characteristics. Manual classification methods are time-consuming, prompting the need for automated solutions.

### Problem
The task of classifying stars, galaxies, and quasars presents challenges due to the dataset's complexity, including feature correlation and imbalanced class distributions. Manual classification of celestial objects can be time-consuming, taking minutes to hours. Machine Learning (ML) models offer a solution, leveraging multi-wavelength data to improve classification accuracy and significantly reduce classification time for astronomers. Additionally, the classification task encounters several challenges, such as dealing with heterogeneous data sources where observations from different telescopes or instruments introduce variations in data quality and distribution, necessitating harmonization for accurate classification. Furthermore, temporal variability in spectral characteristics due to cosmic events or observational conditions adds complexity, requiring careful consideration to account for such fluctuations during classification.

## System Overview
The system encompasses several key components and processes essential for accomplishing the ML system. Beginning with data preprocessing, the system undergoes cleaning and standardization to ensure data consistency and uniformity. Feature engineering follows, involving the extraction of relevant features and the creation of new variables to enhance predictive power. Model selection plays a pivotal role, where various ML algorithms like random forests, and gradient boosting, naïve Bayes are explored to identify the most suitable model for the classification task. Subsequently, models are trained on preprocessed data using cross-validation techniques to optimize performance and prevent overfitting. Model evaluation assesses performance using metrics like accuracy and precision, facilitating the selection of the best-performing model for deployment. Lastly, hyperparameter tuning fine-tunes model parameters to further enhance performance and effectiveness. This comprehensive overview underscores the intricate processes involved in developing and deploying a robust ML system for celestial object classification.

## Data Collection
The Sloan Digital Sky Survey DR17 dataset, consisting of 100,000 observations with 17 features, serves as the foundation for our classification task.

## Components of the ML System
- **Data Preprocessing:** Ensuring the dataset's quality and consistency.
- **Feature Selection:** Identifying relevant features and removing redundant ones.
- **Model Selection:** Experimenting with various ML algorithms to identify the most suitable ones.
- **Model Evaluation:** Using metrics like accuracy and precision to assess performance.
- **Hyperparameter Tuning:** Fine-tuning model parameters to enhance performance.

## Conclusion
After employing Randomized Search to find the optimal parameters, the Random Forest model emerged as the optimal choice, demonstrating the highest accuracy among the models evaluated. By fine-tuning parameters like the minimum samples split, the number of estimators, maximum depth, and minimum samples leaf, the Random Forest model achieved superior performance. This outcome underscores the effectiveness of Random Forest in accurately classifying astronomical objects in the dataset. Based on rigorous evaluation and parameter optimization, Random Forest stands out as the most suitable model for the task at hand, offering robust predictive capabilities for classifying celestial objects.

---

Feel free to customize this README file further to better suit your project's needs!
