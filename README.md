# Few-shot-learning-based-breast-cancer-detection-using-multi-task-learning
Designed and trained a model to perform multi-tasks at the same time using a handful set of images 

Datasets used:
1) 'ICIAR' for 2 class classification
2) 'BreaKHis' for primary and finegrain classifications

The motivation of the project work is to develop a model which is capable for learning multi tasks at the same instant of time using very few images for training.

The notebook named **k_iciar_enetb0_m1_Multitask_Few_shot_Breakhis.ipynb**  contains code to train the base model on the _ICIAR_ dataset for 2 classes (i.e. Benign and Malignant)

> Model1.h5 is pretrained on the 'ICIAR'.

The jupyter notebook named **_git_mtl2_enetb0_m1_Multitask_Few_shot_Breakhis.ipynb_** contains codes for tuning and re-training the previously trained **EfficientB0** on the BreaKHis dataset for 2 class (Primary) classification and 8 class (Finegrain) classification.

> mtl2_enetb0_m1 folder contains Keras model which is trained on the BreaKHis for multi-tasking. 

