# Italy-Trigger-Word-Detection

In this work we will see how to use works a triggerword detection with Keras implementation. Our input will be the word "Italy".

How to Run Require Python 3.5+ and Colab/Jupiter Notebook

Other requirements:
 - !pip3 install pydub
 - !pip3 install h5py
 - !pip3 install scipy
 - !pip3 install matplotlib
 - td_utils.py

Data Synthesis

1) The first step is to create a dataset for our triggerword detection algorithm, so we will record a mix of positive words ("italy") and negative words (other words than italy) under different backgrounds. The people who recorded the words are of different nationalities in different environments.

2) After we will compute a spectogram of the audio. The spectogram tells us how much different frequencies are in an audio clip at a moment in time and all the information that we will use to structure the next step.

3) Generate a training example using the positive, negative and background clips.

4) Generate a full training set (synthetized audio)

5) Generate a development set (real condition)

Model

1) Our Hotword detected model will use 1-D convolutional layers, GRU layers, and dense layers.

2) Fit the model

3) Test the model

Prediction

1) Test on dev set

Create Examples
