# Lithofacies Classification Using Machine Learning and Deep Learning for Unconventional Tight Sandstone Reservoirs: Krishna–Godavari Basin

Keya Dobriyal

Department of Computer Science and Engineering, 
Amity School of Engineering and Technology, Amity University, Noida, Uttar Pradesh, India

Research carried out at GEOPIC, Oil and Natural Gas Corporation Limited (ONGC), Dehradun

## Abstract
Accurate lithofacies characterization is fundamental to reservoir evaluation, static modelling, completion design and development planning, but conventional interpretation becomes difficult in deep, heterogeneous and high-temperature/high-pressure tight sandstone reservoirs where continuous core is sparse. 

This study presents an integrated data-driven workflow for automated classification of four lithofacies—Tight Sandstone, Sandstone, Siltstone and Shale—from borehole geophysical logs in the Krishna–Godavari (KG) Basin, India. Five representative wells were investigated; three wells with interpreted facies were used for model development and two independent wells were retained for blind validation. 

Conventional measurements comprising Gamma Ray (GR), Bulk Density (RHOB), Neutron Porosity (NPHI), Deep Resistivity (RT), Compressional Sonic (DTCO) and Shear Sonic (DTSM) were integrated with derived petrophysical, elastic and geomechanical attributes. Data conditioning included missing-value treatment, quality control, normalization/scaling, feature engineering and label encoding. Twelve supervised machine-learning algorithms and nine deep-learning architectures were benchmarked using stratified five-fold cross-validation. 

The three strongest models in each branch were subsequently combined through probability-based ensemble learning and optimized using randomized hyperparameter search. CatBoost, LightGBM and XGBoost formed the best machine-learning ensemble, which achieved 92.82% accuracy, 92.79% weighted F1, Cohen’s Kappa of 0.9013 and Matthews Correlation Coefficient (MCC) of 0.9014. The deep-learning ensemble comprising Dense Neural Network, ResNet and CNN achieved 91.07% accuracy, with weighted F1 of 90.98%, Kappa of 0.8769 and MCC of 0.8774. 

The principal confusion occurred between Tight Sandstone–Sandstone and Siltstone–Shale, consistent with overlapping petrophysical signatures near gradual facies boundaries. Blind-well validation demonstrated strong generalization. 

The results indicate that integrated petrophysical and rock-physics attributes, combined with gradient-boosting ensembles, provide an effective and scalable approach for automated lithofacies prediction in structured well-log datasets.

## Declarations
### Code Availability
The code developed for data preprocessing, feature engineering, machine-learning modelling, evaluation, and hydraulic fracturing interval identification and ranking is available from the corresponding author upon reasonable request. The code will be made publicly available in an appropriate repository following publication.

### Data Availability
The study uses proprietary well-log data provided for research purposes. Although the dataset has been anonymized and depth information associated with reservoir pay intervals has been modified to prevent identification, the underlying data remain proprietary and cannot be publicly shared because the original information may potentially be reverse-engineered. Access to the data is therefore subject to the applicable data-ownership and confidentiality restrictions.

### Ethics Approval
Ethical approval was not required for this study because it involves subsurface geological and petrophysical data and does not involve human participants, human subjects, identifiable personal information, or animal experimentation.

### Competing Interests
The authors declare that they have no competing interests relevant to this study.

### Funding
No specific external funding was received for this study.

### Author Contributions
All authors contributed to the study conception, methodology, analysis, interpretation of results, and preparation and revision of the manuscript. All authors approved the final version of the manuscript. The current research was carried out as part of internship at Oil and Natural Gas Corporation and Views expressed in this paper is of the authors only and not necessarily be of ONGC.

## Acknowledgement:
I would like to thank everyone who helped me in any capacity towards the completion of this project. Your support and valuable suggestions towards the work have been very important for the success of my internship project.

The authors are highly grateful to the Head of Institute-Advanced Training Institute, Oil and Natural Gas Corporation Limited (ONGC) for giving an opportunity to do the summer internship at the Geodata Processing and Interpretation Centre (GEOPIC).

I am thankful to Ms. Nebula Bagchi (Executive Director - Head of GEOPIC), a geologist by training for her support and guidance. We express our deep sense of gratitude to Dr. Santosh Kumar Sahu (Superintending Programming Engineer) for his constant support, guidance, providing me the necessary data and encouraging us to complete this work successfully. I also am thankful to all the guides and reviewers for their valuable suggestions towards the improvement of the manuscript. I would like to express my gratitude to my father a geologist J P Dobriyal (Executive Director - Chief of Exploration and Development Directorate ONGC) for ingraining geology since childhood.

Finally, I would like to thank Amity University and the Department of Computer Science & Engineering for providing the platform for a valuable industrial exposure. I also extend my sincere thanks and regards to my faculty mentor Dr. Manoj Kumar Shukla, Professor at the Amity School of Engineering and Technology for his continuous support and encouragement throughout the period of my internship.
