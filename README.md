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


screenshot![1](https://user-images.githubusercontent.com/91838916/179020061-184851e0-d36c-4b8e-b99c-ef7abe1c1dc4.png)


screenshot[2](https://user-images.githubusercontent.com/91838916/179020209-3b35a028-0d8f-4007-8631-e4704b2507d9.png)

   
screenshot[3](https://user-images.githubusercontent.com/91838916/179020325-016ceecc-1fa6-4af3-bb2b-57643f42f513.png)




screenshot[4](https://user-images.githubusercontent.com/91838916/179020424-ef07dd9e-0079-48ae-af5a-dffa0c25e615.png)



screenshot[5](https://user-images.githubusercontent.com/91838916/179020511-0a57eedb-b80e-463e-be7b-a2d0adf19e3a.png)

!screenshot[6](https://user-images.githubusercontent.com/91838916/179020637-b6fdcf19-e65d-414c-809c-7db6e2fa0e47.png)

Azure Services Used


Azure Machine Learning
Azure Virtual Machine
Azure Notebooks


