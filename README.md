# About

This is part of a project that I made for a robotics company which takes a users' speech and converts it to text in-order to generate a response<br>
NOTE : This only focuses on Speech to Text-(Conv1d approach) aspect of that project.  <br>

## Table of Contents:<br>

1) Brief Report<br>
2) Architectural Diagram<br>



### Basic Rundown of working:

This is just to understand how things work. Look into Report and Architectural Diagram for more details

1. I first Import and Visualize the dataset I have

![alt text](https://github.com/Satvarsh/Conv1d-SpeechToText/blob/image---Personal-Use/visualize.PNG)

2. Caclulate the count and duration of the audio

![alt text](https://github.com/Satvarsh/Conv1d-SpeechToText/blob/image---Personal-Use/2nd.PNG)
![alt text](https://github.com/Satvarsh/Conv1d-SpeechToText/blob/image---Personal-Use/duration.PNG)

3. Processing the audio to segregate and create paths

4. Create Conv1D model architecture 

5. Test the data (Below is diagnostic plot for a batch of 16

![alt text](https://github.com/Satvarsh/Conv1d-SpeechToText/blob/image---Personal-Use/diagnostic%20plot.PNG)

6. Get the output

![alt text](https://github.com/Satvarsh/Conv1d-SpeechToText/blob/image---Personal-Use/image.png)

### Version History:

```
0.1 - Testing and establishing more data sets
0.2 - Using Librosa library in more places
0.21 - Used multi-classification approach
0.3 - Improving sampling rate, durational requirements to increase speed via scipy
0.31 - Forcedlibrary versions to prevent compatibility errors
0.4 - Added support to use Tensorflow backend libraries form system sites (--systemsite)
0.41 - Created and activated new virtual environment
0.5 - Added a fourth Conv1d Layer
0.6 - Enhanced loss function
0.61 - Implemented EarlyCheckpoints (MANDATORY)
0.62 - Increased Training Model batch size to 32 (Efficient and faster)
0.7 - Using SoundFile, SoundDevice instead of PyAudio
0.71 - Function to record and writing the data
0.72 - Established sample rate as 16000

Time Frame: 28 Days
```
### Libraries Required:

```
Matplotlib, kiwisolver, cycler, Jit, librosa, IPython, scipy, numpy, numba (0.48.0 version only)
Pylint, Sklearn, keras, virtualenv, tensorflow, Pyaudio, SoundDevice, requests, SoundFile, darr
```

### Dataset used : https://www.kaggle.com/c/tensorflow-speech-recognition-challenge


