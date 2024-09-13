---
type: PostLayout
title: Speech Emotion Recognition (SER)
date: '2024-08-22'
excerpt: >-
  I developed a Speech Emotion Recognition solution, with the goal of identify
  human emotions from audio recordings. The project uses Python, Keras,
  TensorFlow, and Scikit-learn to train models that predict emotions such as
  happiness, sadness, anger, and calmness from audio inputs.
featuredImage:
  type: ImageBlock
  url: /images/speech-emotion-recognition.webp
  altText: Speech Emotion Recognition
  styles:
    self:
      borderRadius: x-large
bottomSections:
  - type: DividerSection
    title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
  - type: FeaturedItemsSection
    items:
      - type: FeaturedItem
        title: Project Repository
        tagline: ''
        subtitle: ''
        text: >
          Explore the full implementation, including code, data, and detailed
          analysis, on GitHub.
        actions:
          - type: Button
            label: View Project on Github
            altText: ''
            url: 'https://github.com/Shola-Ayeotan/Speech-Emotion-Recognition'
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
    actions: []
    variant: small-list
    colors: bg-light-fg-dark
    styles:
      self:
        margin:
          - mb-20
        padding:
          - pt-0
          - pl-0
          - pb-0
          - pr-0
        justifyContent: center
      subtitle:
        textAlign: center
slug: speech-emotion-recognition
isFeatured: true
colors: bg-light-fg-dark
styles:
  self:
    padding:
      - pt-5
      - pl-5
      - pb-5
      - pr-5
    textAlign: left
    borderColor: border-light
    borderStyle: none
    borderWidth: 0
    borderRadius: none
    flexDirection: col
---
In this project, I developed a Speech Emotion Recognition (SER) model that uses machine learning to identify human emotions from speech. Emotions such as happiness, sadness, anger, and calmness are essential for communication, and this project explores how to automate the process of detecting emotions from audio data.

#### Objective

The primary goal was to create a model that could predict the emotion in a given speech audio file.

**The project involved:**

*   Feature Extraction from audio signals using advanced signal processing techniques.

*   Model Training with both deep learning and traditional machine learning approaches.

*   Deployment of a Flask API for real-time emotion classification.

#### Tech Stack

*   Programming Language: Python

*   Libraries: Scikit-learn, H2O, pandas, numpy, Flask, Seaborn, Matplotlib

*   Containerization: Docker

#### Dataset Description

I used the[ RAVDESS dataset](https://zenodo.org/records/1188976) (Ryerson Audio-Visual Database of Emotional Speech and Song), which includes speech files from actors portraying different emotions.

The dataset contains 7356 files, with emotions: *Neutral, Calm, Happy, Sad, Angry, Fearful, Disgust, and Surprised.* The speech data provided a rich source for training the models, with actors delivering speech in a controlled setting for each emotion.

#### Technologies Used

The project uses the following tech stack:

*   Programming Language: Python,

*   Machine Learning: TensorFlow, Keras, Scikit-learn

*   Audio Processing: Librosa, SoundFile

*   Data Handling: Pandas, Numpy, Matplotlib

#### Implementation Process:

##### Exploratory Data Analysis (EDA)

Before building models, I conducted **Exploratory Data Analysis (EDA)** to understand the structure and distribution of the audio data. Several visualizations were generated to explore the audio features extracted from the dataset.

**Waveforms**: Plots of raw audio waveforms for each emotion were generated to understand the differences in speech patterns across emotions. Emotions like **anger** showed a more pronounced amplitude in the waveform, with frequent peaks and high energy, while **calm** and **neutral** emotions exhibited smoother, less dynamic waveforms.![](/images/Waveform.png)![](/images/Waveform%20Segment.png)

**Spectrograms**: Spectrograms were created to visualize how the frequencies in the speech signals changed over time. Emotions like **fear** and **disgust** displayed distinct patterns in the frequency domain, with more concentrated energy in certain frequency bands.![](/images/Mel%20Spectogram.png)![](/images/Mean%20Mel%20Spectogram%20accross%20frequency.png)****

**MFCC Distribution**: The distribution of **MFCC** values across different emotions was plotted. MFCC captures the overall spectral envelope and provides crucial information about how speech characteristics vary across emotions. Emotions like **happiness** and **surprise** exhibited higher variance in their MFCC values, while emotions like **sadness** and **neutral** had more stable distributions. This reflects the more dynamic nature of speech associated with positive emotions compared to more subdued emotions like sadness.![](/images/MFCCs.png)****

**Chroma Spectogram**: Chroma features, which represent the pitch class (musical notes), were visualized for various emotions. These plots demonstrated differences in pitch class usage across emotions, with some emotions utilizing a wider range of pitch classes than others.

![](/images/Chroma%20Spectogram.png)![](/images/Mean%20Chroma%20Spectogram%20accross%20frequency.png)

##### Feature Extraction

Using the *librosa* library, I extracted several key features from the audio files:

*   **MFCC (Mel Frequency Cepstral Coefficients)**: Captures the timbre of the audio, making it a crucial feature for speech processing.

*   **Chroma Feature**: Indicates the pitch class, useful for identifying the tone of speech.

*   **Zero-Crossing Rate**: Measures how frequently the signal changes sign, giving insight into the energy and sharpness of the speech.

*   **Mel Spectrogram**: Visualizes the power of frequencies over time, providing a broader context of the audio signal.

##### Model Building

I implemented two different modelling approaches:

1.  **Artificial Neural Network (ANN)** using **Keras** and **TensorFlow**.

    *   A deep learning approach with multiple dense layers.

    *   Trained to classify emotions using softmax output.

2.  **MLPClassifier** from **Scikit-learn**.

    *   A traditional machine learning approach with multiple hidden layers.

    *   Tuned hyperparameters to optimize performance.

##### Model Evaluation

Both models were trained on a **70:30 train-test split**. I evaluated them using metrics such as **accuracy** and **confusion matrix**. The final model achieved over **80% accuracy**, making it effective at distinguishing between various emotions.

#### Deployment

To make the model accessible, I deployed the system as a **Flask API**. This allows users to upload an audio file and receive a real-time emotion prediction. The API is containerized using Docker, enabling easy deployment to platforms like **Heroku** or **AWS**.

Key features of the Flask app:

*   **/predict endpoint**: Accepts audio files and returns an emotion classification.

*   **Real-time interaction**: Users can upload an audio file via a web interface or API call to get instant feedback on the detected emotion.

#### Results

The project successfully implemented a model capable of classifying emotions from speech with high accuracy. By combining advanced audio feature extraction techniques with machine learning, the model can distinguish between multiple emotions with real-time predictions via an API.

#### Future Work

The next steps for this project include:

*   **Improving the model’s accuracy** by incorporating more sophisticated neural network architectures like **RNNs** (Recurrent Neural Networks) or **CNNs** (Convolutional Neural Networks).

*   **Expanding the dataset** to include more varied speech data to make the model more robust across different speakers and environments.

