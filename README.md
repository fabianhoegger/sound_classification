# Enviromental_Sound_Classification

![Rasp](/IMG_20200525_193715.png)
 Raspberry Pi with Webcam

![dist](/class_distribution.png)


Dataset Class distribution
Dataset used : https://www.kaggle.com/mmoreaux/environmental-sound-classification-50<br/>
CNN with 8 layers.
Data extracted are mfccs for 1/10 of a second of audio.


![breath](/log_spec_breathing.png)

Nice articles related
* http://www.practicalcryptography.com/miscellaneous/machine-learning/guide-mel-frequency-cepstral-coefficients-mfccs/
* https://haythamfayek.com/2016/04/21/speech-processing-for-machine-learning.html

## Code
To classify audio (wav),place it in the same directory with make_prediction.py<br/>
and model3.sav files and give as arguments filename and length in seconds.<br/>
**ex. python make_prediction.py filename.wav 7**
