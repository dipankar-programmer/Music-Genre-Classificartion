# Music-Genre-Classificartion
In this project I have made a music genre classifier using FFT and MFCC (look at the MGC_Sample.ipynb to understand the basics of MFCC and FFT)
The basic idea of the model is-

<img width="829" alt="image" src="https://user-images.githubusercontent.com/68048105/146890500-26d16e62-26db-43d6-829c-f2dd144ee568.png">

in this the music data is converted to a spectogram using FFT Transformation and then applying STFT to the data.
Then the spectogram data is stored into a json file, upon which diffrent models are being made. 

The Dataset: https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification
