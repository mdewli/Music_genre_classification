# Music_genre_classification
Classify music data of 10 genres namely, blues, classical, country, disco, hiphop, jazz, reggae, rock, metal and pop. 
Each genre consists of 100 sound clips.

Before training the classification model, we have to transform raw data from audio samples into more meaningful representations. (sample the audio data, make it monotone and ensure that all files have same bit-depth)

We then need to extract meaningful features from audio files. To classify our audio clips, we will choose 5 features, i.e. Mel-Frequency Cepstral Coefficients, Spectral Centroid, Zero Crossing Rate, Chroma Frequencies, Spectral Roll-off. All the features are then appended into a .csv file so that classification algorithms can be used.

Once the features have been extracted, we use existing classification algorithms to classify the songs into different genres. 

Select the best performing algorithm

Recommend Music beased on cosine similarity

Acknowledgements
The GTZAN dataset is the most-used public dataset for evaluation in machine listening research for music genre recognition (MGR). The files were collected in 2000-2001 from a variety of sources including personal CDs, radio, microphone recordings, in order to represent a variety of recording conditions (http://marsyas.info/downloads/datasets.html).
