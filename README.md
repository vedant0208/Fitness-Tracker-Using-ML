# Fitness Tracker using Machine Learning

## Overview
This project aims to develop an intelligent fitness tracker that classifies different barbell exercises based on motion sensor data. The tracker automatically recognizes exercises, counts repetitions, and provides real-time feedback to improve the accuracy of fitness tracking. By leveraging machine learning techniques, this project enhances traditional fitness tracking, which often struggles with precise movement classification.

## Features
- **Automatic Exercise Recognition:** Classifies different barbell exercises using machine learning models.
- **Repetition Counting:** Custom algorithm detects movement patterns and accurately counts repetitions.
- **Real-time Feedback:** Provides insights into workout patterns to help optimize training routines.
- **Data-Driven Insights:** Uses accelerometer and gyroscope data for precise tracking.
- **Machine Learning-Powered Classification:** Implements multiple models, including Naive Bayes, SVM, Random Forest, and Neural Networks.

## Objective
The primary objective of this project is to create a system that accurately classifies exercises and counts repetitions, providing users with valuable insights into their workout performance. Traditional fitness tracking methods lack precision, and this project addresses that limitation using machine learning techniques.

## Dataset
The dataset was collected using accelerometer and gyroscope sensors. The data acquisition process involved recording sensor readings at various time intervals while performing different barbell exercises.

### Data Preprocessing
- Cleaning and normalizing raw sensor data.
- Handling missing values and removing noise using Pandas, NumPy, and SciPy.
- Applying feature engineering techniques such as Principal Component Analysis (PCA), frequency analysis, and low-pass filtering to extract meaningful patterns.
- Outlier detection using Chauvenet’s criterion and local outlier factor to improve prediction reliability.

## Methodology
1. **Data Collection:** Motion sensor data was collected from accelerometers and gyroscopes during different barbell exercises.
2. **Preprocessing:** Data was cleaned, normalized, and processed using feature engineering techniques.
3. **Model Selection & Training:**
   - Experimented with multiple machine learning models:
     - Naive Bayes
     - Support Vector Machines (SVMs)
     - Random Forest
     - Neural Networks
   - Hyperparameter tuning was applied for optimal performance.
4. **Evaluation & Optimization:**
   - Models were evaluated based on accuracy, precision, recall, and F1-score.
   - The best-performing model was selected for deployment.
5. **Repetition Counting:**
   - Developed a custom algorithm to count repetitions by analyzing movement patterns and detecting peaks in sensor data.
6. **Deployment:**
   - The final model was implemented into a fitness tracking system that provides real-time classification and repetition counting.

## Technologies Used
- **Programming Languages:** Python
- **Libraries:** Pandas, NumPy, SciPy, Scikit-learn, Matplotlib, Seaborn
- **Machine Learning Algorithms:** Naive Bayes, Support Vector Machines, Random Forest, Neural Networks
- **Data Processing Tools:** Pandas, SciPy, NumPy
- **Visualization:** Matplotlib, Seaborn

## Challenges Faced
- **Data Noise:** Sensor data contained noise that needed to be filtered for better accuracy.
- **Feature Extraction:** Extracting relevant features from raw accelerometer and gyroscope data was challenging.
- **Model Selection:** Experimented with multiple machine learning models to find the best one for exercise classification.
- **Repetition Counting Accuracy:** Developed a robust peak detection algorithm to ensure accurate rep counting.

## Outcomes & Impact
- Achieved high accuracy in exercise classification and repetition counting.
- Provided users with real-time feedback on their workouts.
- Showcased the effectiveness of machine learning in improving fitness tracking accuracy.
- Demonstrated expertise in working with real-world sensor data and building end-to-end machine learning solutions.

## Future Enhancements
- Integrating deep learning models for better accuracy.
- Implementing real-time tracking on mobile devices.
- Expanding the dataset with more exercises and variations.
- Developing a user-friendly dashboard for workout analytics.




