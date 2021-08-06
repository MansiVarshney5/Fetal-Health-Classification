# Fetal-Health-Classification
## Classify the health of a fetus as Normal, Suspect or Pathological using CTG data
**Data Source:** Cardiotocography Data Set
https://archive.ics.uci.edu/ml/datasets/cardiotocography

### Problem Statement:
Cardiotocography can be used to monitor a baby's heart rate and a mother's contractions while the baby is in the uterus. CTG is used both before birth and during labour, to monitor the baby for any signs of distress. By looking at various different aspects of the baby's heart rate, doctors can see the condition of a baby. The vast majority of these deaths (94%) occurred in low-resource settings, and most could have been prevented.   

This dataset contains 2126 records of features extracted from CTG, which were then classified by experts into 3 classes:

- Normal      
- Suspect     
- Pathological 

![image](https://user-images.githubusercontent.com/81185267/128505711-8c452578-0f4e-4e1b-81fe-f9c50a7eb9de.png)
    

### Machine Learning Models:
- Logistic Regression (LR)
- K-nearest neighbors (KNN)
- SVC
- Decision Tree
- Random Forest (RF)

********* Random Forest Results *********                      
Accuracy    :  0.943              
Recall      :  0.943              
Precision   :  0.942          
F1 Score    :  0.943            

                precision    recall  f1-score   support

         1.0       0.95      0.98      0.97       494
         2.0       0.86      0.75      0.80        88
         3.0       0.96      0.88      0.92        52
    accuracy        -        -         0.94       634
    
   macro avg       0.92      0.87      0.90       634                        
weighted avg       0.94      0.94      0.94       634                              




![image](https://user-images.githubusercontent.com/81185267/128506647-c4562e63-5888-475b-941f-1045845d96f5.png)



      
                                                            
---------------------------------------------------------------------------------------------------------------                                                                 
           
### Variable Description: 
**Target variable:**                          
'fetal_health' Tagged as 1 (Normal), 2 (Suspect) and 3 (Pathological)

**Independent variables:**                                  
**baseline value:** FHR baseline (beats per minute)      
**accelerations:** Number of accelerations per second      
**fetal_movement:** Number of fetal movements per second       
**uterine_contractions:** Number of uterine contractions per second        
**light_decelerations:** Number of light decelerations per second      
**severe_decelerations:** Number of severe decelerations per second      
**prolongued_decelerations:** Number of prolonged decelerations per second       
**abnormal_short_term_variability:** Percentage of time with abnormal short term variability     
**mean_value_of_short_term_variability:** Mean value of short term variability     
**percentage_of_time_with_abnormal_long_term_variability:** Percentage of time with abnormal long term variability                   
**mean_value_of_long_term_variability:** Mean value of long term variability                           
**histogram_width:** Width of FHR histogram                    
**histogram_min:** Minimum (low frequency) of FHR histogram                        
**histogram_max:** Maximum (high frequency) of FHR histogram                                       
**histogram_number_of_peaks:** Number of histogram peaks                       
**histogram_number_of_zeroes:** Number of histogram zeros                        
**histogram_mode:** Histogram mode                       
**histogram_mean:** Histogram mean                       
**histogram_median:** Histogram median                       
**histogram_variance:** Histogram variance                       
**histogram_tendency:** Histogram tendency                       

