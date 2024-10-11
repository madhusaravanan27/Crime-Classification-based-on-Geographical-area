**Crime Classification Based on Geographical Area**:

**Project Overview**:

This project aimed to classify and understand crime patterns by geographical areas using various data analysis and machine learning techniques. The goal is to provide insights into crime severity, victim demographics, and temporal patterns to aid decision-making for real estate agents, residents, law enforcement, and the general public.

**Technologies Used**:

**Python**: Programming language used for data processing and model building

**Pandas/Numpy**: For data manipulation and preprocessing

**Seaborn/Plotly**: For visualizing data with bar charts, histograms, and categorical plots

**Folium**: For creating geospatial visualizations such as heatmaps

**KMeans Clustering:** For identifying geographic crime hotspots

**Scikit-learn**: For building classification models including RandomForest, XGBoost, and Logistic Regression

**SMOTE (Synthetic Minority Over-sampling Technique)**: Used for handling class imbalance in classification tasks

**SimpleRNN (Recurrent Neural Network)**: For crime prediction using neural networks

**Key Accomplishments**

**1. Data Preparation and Cleaning**:

Data Sourcing: 
Crime data was sourced from the Los Angeles Police Department, including crime type, location, date, time, and victim details.

Cleaning Process:
The dataset was cleaned by renaming columns, handling missing values, and addressing outliers, ensuring reliability and accuracy for further analysis.

**2. Feature Engineering**:

Crime Severity Categorization:
Crimes were categorized based on severity (e.g., 'High Severity' for violent crimes like homicide and 'Low Severity' for petty theft).
Victim Demographics: Features were added to represent demographic data such as victim age, gender, and ethnicity, enabling deeper insights into crime patterns.

**3. Geographical and Demographic Analysis**:

Heatmap Creation: 
Using the Folium library, interactive heatmaps were created to identify crime-prone areas across Los Angeles.

Geospatial Clustering: 
KMeans clustering was applied to uncover geographic hotspots where certain crimes are more prevalent.

Victim Demographics: 
Bar charts and visualizations were used to break down crime incidents by victim age, gender, and ethnicity, revealing patterns in crime targeting.

**4. Time-Based Analysis**:

Temporal Trends: 
Analyzed crime occurrences over various time frames (year, month, day) to reveal patterns, such as the significant rise in crimes on Fridays and in July.

Time Series Analysis: 
Conducted temporal analysis of crime trends from 2020 to 2023, uncovering notable fluctuations in crime rates.

**5. Exploratory Data Analysis (EDA):**

Crime Distribution by Location:
Bar charts were generated to show the frequency of crimes based on location type, revealing a concentration of reports in residential areas and streets.

Demographic Analysis:
EDA focused on crime distribution by ethnicity and gender, highlighting disparities across different groups.

**6. Machine Learning Models**:

Classification Models:
Applied RandomForest, XGBoost, and Logistic Regression classifiers to predict crime occurrences before and after SMOTE application to handle class imbalance.

Model Performance: 
Pre-SMOTE, the RandomForest classifier had a higher accuracy (75%) and recall for the majority class (0.90). Post-SMOTE, the overall accuracy of both RandomForest and XGBoost dropped slightly to 68%.

Neural Network (SimpleRNN): 
Trained a SimpleRNN model for crime classification, achieving a test accuracy of 50.62% after training for 20 epochs.

**7. Data Visualizations**:

Crime Frequency by Location and Victim Demographics: 
Created detailed visualizations using Seaborn and Plotly to illustrate crime reports by location, age, gender, and ethnicity.

Correlation Heatmap: 
Generated a correlation heatmap to highlight relationships between crime attributes like time occurred, latitude, and longitude.

Conclusion and Future Scope:
The project successfully created a system to classify and analyze crimes based on geographical data, aiding in crime prevention strategies and providing insights for law enforcement and the general public. Future work could involve refining the machine learning models, improving accuracy, and expanding the system to other cities for broader applicability.

