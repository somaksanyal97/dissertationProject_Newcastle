# Knee Osteoarthritis Progression Prediction

Knee osteoarthritis (KOA) is a prevalent chronic disease characterized by pain and progressive, irreversible structural damage to cartilage and joints. Despite the absence of a definitive cure, understanding and predicting the future progression of KOA is crucial for effective clinical management and the development of disease-modifying osteoarthritis drugs (DMOADs). 

This study aims to predict the progression of KOA as a multi-class classification problem, utilizing baseline feature datasets from approximately 300 KOA patients, along with their progression measures recorded over a two-year period. The data is sourced from the APPROACH (Applied Public-Private Research enabling OsteoArthritis Clinical Headway) study and combines multiple datasets internally.

We apply various machine learning (ML) algorithms, including **Random Forest, k-Nearest Neighbors, Artificial Neural Networks, and Decision Trees,** to identify the best feature combinations and corresponding ML models. These models are evaluated based on their accuracy and macro F1 score. The most effective model, achieving an **accuracy of 66.6% and a macro F1 score of 36.1%**, resulted from combining the Tomography and Questionnaires datasets and training them on a Random Forest classifier.

Key features contributing to the model's success are identified using Permutation Feature Importance. Additionally, the individual contributions of these top features are visually represented with summary plots using SHAP (SHapley Additive exPlanations).

## Key Findings
- **Best Model:** Random Forest classifier
- **Accuracy:** 66.6%
- **Macro F1 Score:** 36.1%
- **Important Features:** Identified using Permutation Feature Importance
- **Feature Contributions:** Visualized with SHAP summary plots

The accuracy would improve significantly if the same model is trained on larger datasets.

This repository contains the code and datasets used in the study, offering insights into the prediction of KOA progression and the potential for further research and development in this area.

You can find the full dissertation [here](https://github.com/somaksanyal97/dissertationProject_Newcastle/blob/main/Dissertation%20Final.pdf).
