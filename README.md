# Greenhouse_Plant_Growth Analysis with Model Prediction
Advanced IoT-Based Smart Greenhouse Dataset (Agriculture Growth Monitoring).

# About Dataset
The Advanced IoT Agriculture Dataset captures detailed physiological and morphological measurements of plants grown under two greenhouse settings (IoT‑enabled vs. traditional) at Tikrit University’s Agriculture Lab. Compiled by Mohammed Ismail Lifta (2023–2024) under the supervision of Prof. Wisam Dawood Abdullah, it comprises 30,000 records spanning 14 variables that quantify chlorophyll levels, growth rates, biomass (wet/dry weight), root metrics, and more, alongside a final categorical Class label.

# Aim Of The Project:
"Can we accurately predict greenhouse type and analyze plant growth patterns using environmental sensor data, 
and how do machine learning techniques help in understanding the impact of IoT on crop health and productivity?"

# Steps 1:
 **To Analysis:**
 - Average of chlorophyll in the plant for both IoT and Traditional green house
 - Average plant height rate for both IoT and Traditional green house
 - Average wet weight of the growth vegetative for both IoT and Traditional green house
 - To check if their is any influence that can have effect on both Green house types.
 # Step 2:  
  **Model Testing**:
  **Research Questions to Support Model Testing Are**:-
 - Can environmental sensor data predict whether a plant is grown in a traditional or IoT-based greenhouse?
 - What features most influence classification between greenhouse types?
 - Can we use clustering to discover natural groupings of greenhouse setups without knowing class labels?
 - How do IoT-based setups impact key growth indicators compared to traditional ones?
 - Which machine learning models offer the best generalization on unseen greenhouse conditions?
   
  **Model Evaluation and Iteration Supervised Learning Tasks**

 - Train-test split
 - Create a model, train the model (fit) and Predict the result.
 - Correlation matrix
 - Target: class (multiclass classification)
 - Models: Logistic Regression, Decision Trees, KNN, SVM, Naive Bayes, Ensemble models
 - Objective: Classify greenhouse type (SA–SC vs TA–TC or just A–C for broader analysis)
 - Metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix
# Features Inputs Will Be:
 - Random	Sample batch ID (e.g., R1, R2, R3)	String
 - ACHP	Average chlorophyll content (photosynthetic pigment)
 - PHR	Plant height growth rate
 - AWWGV	Average wet weight of vegetative growth	
 - ALAP	Average leaf area per plant	
 - ANPL	Average number of leaves per plant	
 - ARD	Average root diameter	Float
 - ADWR	Average dry weight of roots	
 - PDMVG	% dry matter in vegetative growth	
 - ARL	Average root length	Float
 - AWWR	Average wet weight of roots
 - ADWV	Average dry weight of vegetative parts
 - PDMRG	% dry matter in root growth	Float
 - Class	Experimental group label (SA, SB, SC, TA, TB, TC)
   
# Technologies To Be Use:

 - Python 3.x
 - Jupyter Notebook
 - pandas
 - numpy
 - matplotlib
 - KNeighborsClassifier
 - train_test_split
 - RandomForestClassifier
 - LabelEncoder, StandardScaler
 - Accuracy_score, classification_report, confusion_matrix.
# Note: 
 - There might be some changes as the reserach is ongoing.


