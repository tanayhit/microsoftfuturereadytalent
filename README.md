Gender and Emotion Detection using Audio




Description



Gender and Emotion recognition by voice is a technique in which you can determine the gender category of a speaker by processing speech signals, in this tutorial, we will be trying to classify gender by voice using the TensorFlow framework in Python.

Gender recognition can be useful in many fields, including automatic speech recognition, in which it can help improve the performance of these systems. It can also be used in categorizing calls by gender, or you can add it as a feature to a virtual assistant that is able to distinguish the talker's gender.




work flow


Broadly speaking there are two category of features:

Time domain features


These are simpler to extract and understand, like the energy of signal, zero crossing rate, maximum amplitude, minimum energy, etc.



Frequency based features

are obtained by converting the time based signal into the frequency domain. Whilst they are harder to comprehend, it provides extra information that can be really handy such as pitch, rhythms, melody etc

MFCC is well known to be a good feature. And there's many ways you can slice and dice this one feature. But what is MFCC?
It stands for Mel-frequency cepstral coefficient, and it is a good "representation" of the vocal tract that produces the sound. Think of it like an x-ray of your mouth.



modeling


The architecture of the model is based on a few sources that I've seen before such as Kaggle and Stackoverflow. I'm unable to find the source but safe to say this particular format works quite well and is fast, although I've used GPU


