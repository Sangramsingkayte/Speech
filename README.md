# # Text-to-Speech Recipe
Users can create speech signals from an input text by using text-to-speech (TTS), also referred to as speech synthesis. Popular TTS and Vocoder models, such as Tacotron 2, are supported by SpeechBrain (e.g, HiFIGAN).

# # Speech Separation Recipe
With SpeechBrain, a SepFormer model for speech source separation was created, and it was pretrained on the WHAMR! dataset, which is essentially a variation of the WSJ0-Mix dataset with ambient noise and reverberation. We strongly advise you to learn more about SpeechBrain for a better experience. The model's performance on the test set of the WHAMR! dataset is 13.7 dB SI-SNRi.

# # Speech Enhancement Recipe
Several techniques are currently accessible in SpeechBrain, including spectrum masking, spectral mapping, and time-domain improvement. Additionally, separation techniques like Conv-TasNet, DualPath RNN, and SepFormer are used.

# # Speaker Recognition Recipe
A wide range of practical applications now use speaker recognition. For speaker recognition, SpeechBrain offers a variety of models, including X-vector, ECAPA-TDNN, PLDA, and contrastive learning.


## References
* http://haythamfayek.com/2016/04/21/speech-processing-for-machine-learning.html
* https://github.com/wiseman/py-webrtcvad
* https://github.com/jameslyons/python_speech_features
* https://github.com/ZhihaoDU/speech_feature_extractor
* http://ibillxia.github.io/blog/archives/
* http://stevemorphet.weebly.com/speech-and-audio-processing
* MFCC
  * http://blog.csdn.net/zouxy09/article/details/9156785
  * http://blog.csdn.net/xmdxcsj/article/details/51228791
  * http://practicalcryptography.com/miscellaneous/machine-learning/guide-mel-frequency-cepstral-coefficients-mfccs/
* Git tutorial
  * https://jingyan.baidu.com/article/2fb0ba4091a21c00f2ec5fbf.html
  * https://jingyan.baidu.com/article/fec4bce2285b56f2618d8bdc.html


