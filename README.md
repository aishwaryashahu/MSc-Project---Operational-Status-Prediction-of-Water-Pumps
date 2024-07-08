# Operational Status Prediction of Water Pumps

## School: Computer Science, University of Nottingham, UK
## Academic Year: 2023-24

### Student Information
- **Name**: Aishwarya Shahu
- **Student ID**: 20607987

## Project Title
**Operational Status Prediction of Water Pumps**

### Module Code
COMPXXXX

## Project Overview
This project explores the application of machine learning techniques to predict the operational status of water pumps in Tanzania. The dataset, sourced from the Taarifa waterpoints dashboard and the Tanzania Ministry of Water, contains detailed attributes of over 59,000 water points across various regions. The study implements a robust methodology encompassing data preprocessing, exploratory data analysis (EDA), and the application of multiple classification algorithms.

### Key Analyses
1. **Data Preprocessing**:
   - **Handling Missing Values**: Addressing missing data in crucial fields like 'installer', 'funder', and 'public meeting'.
   - **Outlier Detection and Removal**: Ensuring a more standardized and normalized data distribution.
   - **Feature Engineering**: Creating new features to enhance model accuracy.
   - **Categorical Encoding**: Converting categorical data into machine-readable formats using one-hot and label encoding.

2. **Exploratory Data Analysis (EDA)**:
   - **Visualization**: Using histograms, scatter plots, and box plots to visualize feature distributions.
   - **Correlation Analysis**: Identifying relationships between features to understand dependencies and relevance for predicting water point functionality.

3. **Machine Learning Models**:
   - **Random Forest**: Known for robustness and handling high-dimensional data.
   - **Gradient Boosting Machines (XGBoost, LightGBM)**: Advanced ensemble techniques for high performance and handling unbalanced data.
   - **K-Nearest Neighbors (KNN)**: Effective in classification by analyzing instance similarities.

### Data Description
#### Dataset
- **Source**: Taarifa waterpoints dashboard and Tanzania Ministry of Water
- **Features**:
  - `amount_tsh`: Total static head (amount of water available).
  - `date_recorded`: Date of data recording.
  - `funder`: Entity funding the water point.
  - `gps_height`: Altitude of the water point.
  - `installer`: Entity installing the water point.
  - `longitude`: Longitude coordinate.
  - `latitude`: Latitude coordinate.
  - `basin`: Basin region.
  - `public_meeting`: Presence of public meeting.
  - `scheme_management`: Management scheme.
  - `scheme_name`: Scheme name.
  - `permit`: Presence of permit.
  - `construction_year`: Year of construction.
  - `extraction_type`: Type of extraction.
  - `management`: Management entity.
  - `payment`: Payment system.
  - `water_quality`: Quality of water.
  - `quantity`: Quantity of water.
  - `source`: Source of water.
  - `waterpoint_type`: Type of waterpoint.
  - `status_group`: Operational status (functional, functional needs repair, non-functional).

### Methodology
1. **Data Acquisition**:
   - Sourced from Taarifa waterpoints dashboard and Tanzania Ministry of Water.
   - Dataset comprises training data with labels and test data without labels for evaluation.

2. **Data Preprocessing**:
   - **Missing Value Treatment**: Imputation techniques for continuous and categorical data.
   - **Outlier Detection and Removal**: Using box plots and IQR scores.
   - **Feature Engineering**: Extracting new features like year and month from 'date_recorded'.
   - **Categorical Encoding**: Using one-hot and label encoding for machine-readable data.

3. **Model Selection**:
   - Decision Trees and Random Forest for handling high-dimensional data.
   - Gradient Boosting Machines (XGBoost and LightGBM) for performance and speed.
   - K-Nearest Neighbors (KNN) for similarity-based classification.

4. **Evaluation Metrics**:
   - Accuracy, Precision, Recall, F1 Score, Confusion Matrix, ROC-AUC Score.

### Key Findings
- **Random Forest**: Achieved highest accuracy of 80.78% and precision of 80.37%.
- **CatBoost**: Demonstrated efficiency with categorical data, achieving accuracy close to Random Forest.
- **KNN**: Showed moderate performance with lower accuracy and precision.

### Conclusion
The study successfully applied machine learning techniques to predict the operational status of water pumps in Tanzania. The findings demonstrate the potential of data-driven methodologies in improving public infrastructure and community health outcomes through predictive maintenance.

## References
1. Khan et al., "Predictive Maintenance with Machine Learning: A Review," IEEE Access, 2020.
2. Li et al., "A Survey on Machine Learning for Water Resources Management," IEEE Access, 2019.
3. Al-Fuqahaa and Salman, "Data Mining for Improved Water Pump Maintenance Scheduling," 2018.
4. DeVries et al., "Can Machine Learning Help Us Manage Rural Water Systems? Lessons Learned from Nicaragua," 2016.
5. Katuwal et al., "Leveraging Mobile Phone Network Data for Water Point Functionality Monitoring in Tanzania," 2020.
6. Redwood et al., "Data Availability and Use for WASH in Tanzania," 2019.
7. Gupta and Kumar, "Predictive Maintenance using Machine Learning Approaches: A Practical Approach," 2018.
8. De Silva and Williams, "Machine Learning Algorithms for Water Network Management," 2017.

---

Feel free to contribute to this project by creating issues or submitting pull requests.
