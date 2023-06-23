# ScreamDetection
Machine Learning model for scream detection.
This project is a sub-part of my main project: "Naariksha-Women Safety App" of my university course: "Innovative Product Development".
The ML model takes .wav format audio input as a dataset which is distributed in 2 folders, "positive"(which actual screams) and "negative"(which contains audio that is not detected as a scream)
Librosa library is used for feature extraction from the dataset. The features are Mel-frequency cepstral coefficients (MFCCs) used for feature extraction from audio files.
