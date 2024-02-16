# Tiny speaker recognition using Keras3

This folder contains code to train and evaluate tiny speaker recognition models using Keras 3.

Since this is for demonstration purposes, the code here is presented in Jupyter Notebooks.

## Dataset

The dataset used for this demonstration is an excerpt of the [Common Voice](https://commonvoice.mozilla.org) dataset in Portuguese (my native language). The excerpt of the Common Voice Delta Segment 16.1 has 5h of validated speech with 100 speakers.

## Models

In this initial demonstration, two models are here presented:
- One [model](https://github.com/epilefarias/tiny_speaker_recognition_keras3/blob/main/models/model_raw.keras) that classifies speech from the raw audio, treating each sample as a one-dimensional vector.
- One [model](https://github.com/epilefarias/tiny_speaker_recognition_keras3/blob/main/models/model_fft.keras) that classifies speech from the spectrogram of the audio, treating each sample as a bi-dimensional matrix.

## Basic instructions

TODO

## Why Keras3?

TODO

