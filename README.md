# Youtube-Vlogger-Personality-Profiling_kaggle
This is a group project for the course Big Data Analytics that I worked on with two other students during my masters.
https://www.kaggle.com/c/bda2021big5/overview

#### Data
The YouTube personality dataset consists of a collection of behavorial features, speech transcriptions, and personality impression scores for a set of 404 YouTube vloggers that explicitly show themselves in front of the a webcam talking about a variety of topics including personal issues, politics, movies, books, etc. There is no content-related restriction and the language used in the videos is natural and diverse.

Your team should employ any of the methods discussed in some detail in Chapter 3 of ISLR (James, Witten, Hastie & Tibshirani, 2017), in combination with creative feature engineering and feature selection, to obtain the best numerical predictions for all the personality axes.

For 80 of the 404 vloggers the personality impression scores are missing. Your method should be used to predict these missing personality scores.

No other methods than the ones mentioned in ISLR chapters 1 through 3 may be used. Doing so disqualifies your team.

Please note that the file format in which you need to upload your team's predictions is different from the file format of the data set.

Detailed data structure
The data is stored in a .zip file. How to extract files from this zip file on the Kaggle platform is demonstrated in the Quick Start Notebook that you can fork on the Kernels tab.

Once extracted, in the working directory you will find a directory called 'youtube-personality' which contains the following files and folders

'YouTube-Personality-audiovisual_features.csv'
'YouTube-Personality-gender.csv'
'YouTube-Personality-Personalityimpressionscores_train.csv'
The 'transcripts' in the zip file contains all the transcripts transcribed from the videos in plain text files. These need to be extracted in a special way. See the Quick Start notebook.

Data corresponding to a single vlogger are identified by the vlogId.
