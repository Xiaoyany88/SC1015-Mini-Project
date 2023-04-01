# SC1015-Mini-Project on predicting Global Supply Chain Outcomes for HIV medicines

## About
This is a Mini Project for SC1015 (Introduction to Data Science and Artificial Intelligence)
which focuses on determining the factors that influence the timeliness of pharmaceutical deliveries to predict delivery of HIV drugs, whether there will be delay.

For a detailed walkthrough, do view our source code

## Contributors: 
- Zhang Xiaoyang (U2121950J) - Data Extraction, Data Visualisation, Random Forest
- Ang Yi Heng Bryan (U2122887A) @ terryaa52034 - Data Resampling and Splitting, k Neigbours
- Chua Shi Wei (U2122805B) - Logistic Regression, GaussianNB, Decision Tree

## Problem Definition
Delays in the supply of commodities result in extra costs in terms of storage, coordination, and most importantly, lost lives in the case of HIV medicines. 
       
This project will use publicly available supply chain data to determine the most important factors in predicting whether HIV drugs are delivered on time or not. 

## Models Used
1. Random Forest
2. K Neighbors
3. Logistic Regression
4. Decision Tree
5. GaussianNB

## Conclusion
- Using appropriate Machine Learning Model, Supply Chain Managers can predict whether their will be a delay in supply HIV medicines. As such, they can modify appropriate variables ad predict what actions should be taken to prevent the delay.
- Based on our machine learning model, we have found out that the factors that caused most of the delays in Supply Chain management are shipment mode, the planned dates between deliveries to the clients and the Line Item Quality.
- Random Forest works best for our dataset which gives highest accuracy and one of the lowest False Positive Rate in predicting whether there's a delay


## What we learn from this project?
- How to handle imbalanced datasets using resampling methods and imblearn package
- Various machine learning models like Random Forest and K Neighbours
- Concepts about F1 Score, Precision and Recall

## References
1.  https://data.pepfar.net/additionalData

2. https://www.unaids.org/en/resources/presscentre/pressreleaseandstatementarchive/2017/july/20170720_PR_Global_AIDS_Update_2017#:~:text=Press%20release-,The%20scales%20have%20tipped%E2%80%94UNAIDS%20announces%2019.5%20million%20people%20on,related%20deaths%20halved%20since%202005&text=The%2090%E2%80%9390%E2%80%9390%20targets,global%20action%20and%20saving%20lives 

3. https://www.stat.berkeley.edu/~breiman/RandomForests/cc_home.htm

4. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4466856/

5. https://www.researchgate.net/publication/222928270_Application_of_machine_learning_techniques_for_supply_chain_demand_forecasting. 



