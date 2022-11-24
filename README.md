
<h1 align="center">  Cat-Dog Audio Classification </h1>
<br/>
 
## Dataset

The dataset consists in many "wav" files for both the cat and dog classes :
- Cat has 164 WAV files to which corresponds 1323 sec of audio
- Dog has 113 WAV files to which corresponds 598 sec of audio

All the WAV files contains 16KHz audio and have variable length.
## Cat
![image](https://user-images.githubusercontent.com/96674419/203718695-700bd783-4299-4f6c-9087-958401bca034.png)
## Dog
![image](https://user-images.githubusercontent.com/96674419/203718720-98c0bf1c-6a13-4b1e-b1de-65c5f832238e.png)

Link to download dataset: [Cats-Dogs Audio Dataset](https://www.kaggle.com/datasets/mmoreaux/audio-cats-and-dogs)


## Feature Extraction - MFCC(Mel-Frequency Cepstral Coefficients)
> The most importent step in ML is extracting features from raw data.

This feature is one of the most important method to extract a feature of an audio signal and is used majorly whenever working on audio signals.

MFCC Features extracted from the Audio signals:

Cat:

![image](https://user-images.githubusercontent.com/96674419/203724825-2fe5d075-24a8-4756-aee3-1ad37f8479a2.png)

Dog:

![image](https://user-images.githubusercontent.com/96674419/203722407-9fe2ec70-cd9a-4e24-b1e1-7e9e7ec5d009.png)



<h2> Convolutional Neural Networks </h2>
<p align="center">Model Architecture<br>
  <img src="https://user-images.githubusercontent.com/96674419/203725125-0cf147c5-df44-494a-ba84-40c17f8222c3.png" width=50% height="750"><p/>

<p>
The Convolutional Neural Network (CNN or ConvNet) is a subtype of Neural Networks that is mainly used for applications in image and speech recognition. Its built-in convolutional layer reduces the high dimensionality of images without losing its information. That is why CNNs are especially suited for this use case. 
</p>

<h3>Output</h3>
<p align="center" width="100%">
    <img width="40%" height="300" src="https://user-images.githubusercontent.com/96674419/203726022-03284d4b-4d29-4f5c-8b19-f27379ac7f74.png">
    <img width="40%" height="300" src="https://user-images.githubusercontent.com/96674419/203726072-6e42a08e-882d-4c6b-8a78-af71db743123.png"
</p>


  
## License
[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)
