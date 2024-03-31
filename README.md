Knee osteoarthritis (KOA) is a common chronic disease with no assured
 cure till date in which patients suffer from pain and irreversible progressive struc
tural damage of cartilage and joints. In order to charter an effective clinical path
 and also for the development of disease-modifying osteoarthritis drugs (DMOADs),
 it is essential that physicians and researchers need to ascertain the nature and ex
tent of future progression of the disease with reasonable accuracy. For the purpose,
 formulation of some robust techniques for such prediction emerges expedient. In
 this direction, the present study approaches the prediction of disease progression in
 KOA patients as a multi-class classification problem based on nearly 300 KOA pa
tients’ baseline feature datasets along with their progression measures (measured for
 a period of 2 years) as class labels. These datasets are taken from the APPROACH
 (Applied Public-Private Research enabling OsteoArthritis Clinical Headway) study,
 internally joined in combinations and are used to multiple machine learning (ML)
 algorithms (Random Forest, k Nearest Neighbors, Artificial Neural Networks, De
cision Trees) to identify the best combinations of features and corresponding ML
 model that would give the most accurate predictions measured by F1 score macro
 and accuracy. In this study, the best model in terms of accuracy (66.6%) and macro
 F1 score (36.1%) was obtained from joining the Tomography and Questionnaires
 dataset and training on Random Forest classifier. The most important features
 contributing to this result are identified using Permutation Feature Importance.
 The individual contributions of each of these top features to the prediction are also
 visually represented with summary plots using SHAP.
