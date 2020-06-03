# Predicting Distracted Drivers  

## Overview  


The National Highway Traffic Safety Administration estimated that in 2018, driver distraction was a factor in about 8 percent of all fatal crashes and 15 percent of all injury crashes. Every day about 8 people were killed and more than 1000 injured in crashes that involved a distracted driver. These estimates may be low as it is challenging to determine distraction in driver fatality crashes, and self-reported distractions are likely underreported. 

Distractions include any activity that takes your attention away from driving and fall in three main categories:   
•	visual: looking at something not related to driving;   
•	manual: taking your hands off the steering wheel; and   
•	cognitive: taking your mind off driving.   

Systems that detect distractions and report them to drivers in real-time could reduce distracted driving accidents and deaths.   

CNN and Transfer Learning models were developed to detect driver distractions and safe driving from dashcam images. 

Of the ten classes of images, the models did well with seven and had trouble with three. 

ResNet50 performed the best with an overall accuracy of 84% and class F1-scores ranging from .58 to .99. 

### Data Preparation and Analysis
 
[Data Wrangling](https://github.com/tcardwell/Predicting-Distracted-Drivers/blob/master/1_Data_Preprocessing.ipynb)    
[Data Augmentation Visualization](https://nbviewer.jupyter.org/github/tcardwell/Predicting-Distracted-Drivers/blob/master/2_Visualize_Data_Augmentation.ipynb)    

### Modeling

[Predicting Distracted Drivers](https://nbviewer.jupyter.org/github/tcardwell/Predicting-Distracted-Drivers/blob/master/3_Model.ipynb)
