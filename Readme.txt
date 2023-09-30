Data Collection:
                *Used a kaggle dataset having audio samples related to emotions happy, sad and many other emotions from which happy and sad was used.
Data Preprocessing and Preparation:
                *Used Mfcc audio feature extraction module from librosa module to obtain numerical features from the audio samples and attached related labels to form dataframe.
                *Reshaped input to fit the required shape of model architecture.
                *Split samples into train and test.
Model architecture:
                *LSTM model as base and used Dense hidden layers.
Model Performance:
                * Training accuracy : 87% max.
                * Testing accuracy : 83%.
Testing:
         *Used random audio sample giving accuract emotion prediction.