# NFL_Player_Contact_Detection_Kaggle

Data: <a ref="https://www.kaggle.com/competitions/nfl-player-contact-detection/data"> Download on Kaggle </a>

About the note.ipynb: An overview about the 2 other files

What I have learned:
+ Way to read and write a video
+ matplotlib.patches
+ advanced usage for pd.merge
+ First time using Data Augmentation for image (using albumentations)
+ Overriden on class Dataset (pytorch)
+ Randomly shift frames for training 
+ pd.interpolate 
+ An "humanbeing" approach for extracting data (using a window 24 and get mean, the same for human)
+ using timm to load sota model 

**Important**:
+ An approach for real Video/Image dataset (instead of pretrained model's naked usage)
+ The insight of problem solving for Video dataset
+ Way to use GPU on Kaggle 
+ Way to extract data for model 