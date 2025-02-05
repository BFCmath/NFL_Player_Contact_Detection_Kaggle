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
+ cudf
+ XGB/ForestInference
+ GroupKFold

![image.png](images/demo.png)

**Important**:
+ An approach for real Video/Image dataset (instead of pretrained model's naked usage)
+ The insight of problem solving for Video dataset
+ Way to use GPU on Kaggle 
+ Way to extract data for model 

**Important 2**:
+ The right approach with this problem is treated it with DS pointview
+ Using only csv and xgb: preprocessing technique
+ Using pretrained CNN model: extract the info from the image that the csv cant provide: action, color, overtime changes 
