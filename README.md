# Music_Genres_Classification

Downloaded the Music Genres dataset from https://www.dropbox.com/s/4jw31k5mlzcmgis/genres.tar.gz

The Dataset contains 10 Genres of music :
## Genres
* Blues
* Classical
* Country
* Disco
* Hip-Hop
* Jazz
* Metal
* Pop
* Reggae
* Rock


* Each Genre contains 100 audio files each of duration 30s.
* we need to convert audio files into wav files

## Models
I have explored the problem using two approaches 
1) Using ANN Model which made use of features such as MFCC's,spectral centroids, extracted features from (Feature_Extraction.ipynb) are in Extracted_Features.csv.Check Music_Genres_classification_ANN.ipynb
2) Using Convolutional Neural Network (CNN) Model which made use of Mel Spectrogram of the Audio Files.check Music_Genres_classification_CNN.ipynb

## Results

ANN model is giving quite good test accuracy of 72.5
