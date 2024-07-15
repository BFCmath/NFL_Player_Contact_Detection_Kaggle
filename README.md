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

![visualize](https://media.discordapp.net/attachments/1261282620000567340/1262352670014967808/image.png?ex=66964909&is=6694f789&hm=98d8221b25b74fcd752323d8e3b6d4e04caff7cf66d9fa51deb5b3ef3f942a5b&=&format=webp&quality=lossless&width=608&height=437)

**Important**:
+ An approach for real Video/Image dataset (instead of pretrained model's naked usage)
+ The insight of problem solving for Video dataset
+ Way to use GPU on Kaggle 
+ Way to extract data for model 

**Important 2**:
+ The right approach with this problem is treated it with DS pointview
+ Using only csv and xgb: preprocessing technique
+ Using pretrained CNN model: extract the info from the image that the csv cant provide: action, color, overtime changes 
