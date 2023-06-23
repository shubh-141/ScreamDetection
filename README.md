# ScreamDetection
## Machine Learning model for scream detection.

This project is a sub-part of my main project: "Naariksha-Women Safety App" of my university course: "Innovative Product Development".

- The ML model takes .wav format audio input as a dataset which is distributed in 2 folders, "positive"(which actual screams) and "negative"(which contains audio that is not detected as a scream)
- Librosa library is used for feature extraction from the dataset. The features are Mel-frequency cepstral coefficients (MFCCs) used for feature extraction from audio files.

4 classification models have been used for training:
- Support Vector Machine SCV
- K-Nearest Neighbour
- Deep Neural Networks
- Hidden-Markov Model

The following are outputs respective to the above-mentioned models:
- SVC
  
  <img width="786" alt="image" src="https://github.com/SAPX14/ScreamDetection/assets/80125084/a8ab5422-998a-4309-8be6-f3da2892b431">

  <img width="457" alt="image" src="https://github.com/SAPX14/ScreamDetection/assets/80125084/58b94564-fd0e-4cec-8b8f-498c1c7f445d">

- KNN

  <img width="716" alt="image" src="https://github.com/SAPX14/ScreamDetection/assets/80125084/38fec0f1-7603-4103-abbf-5cab6f08e549">

  <img width="371" alt="image" src="https://github.com/SAPX14/ScreamDetection/assets/80125084/6ab4c758-4481-48a6-9e6d-ec4188428854">

- DNN

  <img width="1040" alt="image" src="https://github.com/SAPX14/ScreamDetection/assets/80125084/06e84e95-3469-4468-8de8-54bdeadd702d">

  ![image](https://github.com/SAPX14/ScreamDetection/assets/80125084/9b296f0e-ca12-4f78-ad69-7834204e10bb)

  ![image](https://github.com/SAPX14/ScreamDetection/assets/80125084/6b64933f-030f-4dd8-b227-44eed8c1cb32)

- HMM

  <img width="754" alt="image" src="https://github.com/SAPX14/ScreamDetection/assets/80125084/058b8cdf-9b68-4987-b057-8ee8c8d91677">





