


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

Dog:

![image](https://user-images.githubusercontent.com/96674419/203722407-9fe2ec70-cd9a-4e24-b1e1-7e9e7ec5d009.png)

Cat:


<h2> Convolutional Neural Networks </h2>
<p>
CNNs or convolutional neural nets are a type of deep learning algorithm that does really well at learning images. To use them for Audio classification we extract features which look like images and shape them in a way in order to feed them into a CNN. We use the <a href="https://librosa.org/doc/latest/index.html">librosa</a> package to do the same. 
</p>
<a> <img src = "https://miro.medium.com/max/828/1*rFhL3CYygk0gGlHOmlL_Jg.png" height=300> </a>

<h3>Output</h3>
<a> <img src = "https://user-images.githubusercontent.com/91772980/202911090-57ef2c4a-591c-4206-8f80-c7a3b1da618a.png" height=400> </a>

<h2> Recurrent Neural Networks </h2>
<p>
Recurrent Neural nets are a type of deep learning algorithm that can remember sequences. Audio data tends to follow a pattern which can be exploited using RNNs to classify them.
In contrast to the CNN model's results we decide to use a stateful LSTM thats allows us to simplify the overall network structure. All we need here is the LSTM layer followed by a Dense layer.
</p>
<a> <img src="https://miro.medium.com/max/1100/1*LZUF32AYHYXIL1WBuyAneg.webp" height=300></a>
<h3>Output</h3>
<a> <img src="https://user-images.githubusercontent.com/91772980/202911103-84ab80c7-98f0-46da-882f-743c19ab9141.png" height=300> </a>




## Contributors
<a href="https://github.com/gautam-j/gautam-j/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=gautam-j/gautam-j" />
</a>
<a href="https://github.com/brijes-h/brijes-h/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=brijes-h/brijes-h" />
</a>
<a href="https://github.com/Manishankar9977/Manishankar9977/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Manishankar9977/Manishankar9977" />
</a>
<a href="https://github.com/jahnavidarbhamulla/jahnavidarbhamulla/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=jahnavidarbhamulla/jahnavidarbhamulla" />
</a>


  
## License
[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)
