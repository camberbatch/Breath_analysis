# Breath analysis
This repository contains the source data and scripts for processing data used in the thesis "Diagnostics possibilities of lung cancer using direct breath analysis with electronic nose system based on semiconductor gas sensors". Kononov A.S. (Saint-Petersburg, SPSU).

Content:

Chapter 2. Experimental details

- file "MS_1_calibration_data.csv": tabular data with sensor responces [µS*s] of calibration samples for n-Heptane, Propan-1-ol, Ethylbenzene for multysensory system (MS1) used in medical study
- file "Calibration parameters of MS-1.ipynb": jupyter notebook for calibration parameters calculation

Chapter 3. Medical study
- file "medical_study_data.csv": tabular data with sensor responces [S*s] of exhaled breath samples in medical study conducted using multysensory system (MS1) for 118 participants. Column description (age: age of participants; sex: 1 - male, 0 - female; smoking: 1 - active or former (<10 years); 0 - no or former (>10 years); LC_stage: 1 - I, 2 - II, 3 - III, 4 - IV; LC_type: 1 - NSCLC, 0 - SCLC; Group: 1 - LC group, 0 - healthy group; lscm: additional feature)

- file "medical_study_notebook.ipynb": jupyter notebook for explanatory data analysis and solution of classification task 

Chapter 4. Calibration transfer

- file "MS 2.1 - 2.2. Samples_mixtures.csv": tabular data with sensor responces [S*s] of one-component calibration gas mixture samples for for n-Heptane, Propan-1-ol, o-Xylene measured on two multysensory systems (MS2.1 and MS2.2) for evalution of calibration transer methods efficiency
- file "MS_2.1 - 2.2. Samples_indidual VOCs.csv": tabular data with sensor responces [S*s] of three-component gas mixture samples for n-Heptane, Propan-1-ol, o-Xylene measured on two multysensory systems (MS2.1 and MS2.2) for evalution of calibration transer methods efficiency
- file "calibration_transfer_notebook.ipynb": jupyter notebook for evaluation of calibration transer methods efficiency on two classification tasks
