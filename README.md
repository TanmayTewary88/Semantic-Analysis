# Semantic Analysis of Short Videos

## Introduction
This project focuses on the semantic analysis of short videos, converting them to text, and applying Natural Language Processing (NLP) techniques to extract key meanings, emotional tones, and themes. By combining video, audio, and textual analysis, we dive deep into understanding the content beyond simple visual and audio recognition.

## Objectives
- Video to Audio Conversion: Convert video files into audio files.
- Audio to Text Transcription: Transcribe the audio into text for further analysis.
- Semantic Analysis: Perform tasks like Named Entity Recognition (NER), semantic similarity, sentiment analysis, and topic modeling on the textual data.
- Context & Sentiment Understanding: Analyze the meaning, context, and emotional tone of the video content.

## Functional Requirements
- Speech-to-Text Conversion: The system should accurately transcribe spoken words in the video to text.
- NLP Techniques: Extract key entities, sentiments, and themes from the text.
- Named Entity Recognition (NER): Recognize and classify entities like names, places, organizations, dates, and events.
- Sentiment Analysis: Determine if the sentiment of the video is positive, negative, or neutral.
- Topic Modeling: Identify and categorize the main themes or topics in the videos.
- Multilingual Support: The system supports multiple languages for a broader analysis scope.

## Project Structure
- Corpus: A collection of over 300 short videos from various genres like Motivational, English-speaking, and Animation. The videos were downloaded from YouTube Shorts, social media platforms, and TikTok.
- Dataset: Videos are stored in genre-specific folders for easy access and analysis. The dataset is used to train models and evaluate performance through sentiment analysis and other NLP tasks.

## Installation and Setup
To run this project locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/semantic-analysis-short-videos.git
    cd semantic-analysis-short-videos
    ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the main scripts:
    - Video to Audio conversion:
        ```bash
        python video_to_audio.py
        ```
    - Audio to Text transcription:
        ```bash
        python audio_to_text.py
        ```
    - NLP and Sentiment Analysis:
        ```bash
        python nlp_analysis.py
        ```

## Dataset
The dataset was created from scratch, consisting of short videos from various platforms, categorized into different genres for easy analysis. 

The corpus includes:
- **Motivational Videos**: Sentiment analysis was performed on 20, 50, and 100 videos, resulting in positive polarity bias due to the nature of the content.
- **English-Speaking Videos**
- **Animated Videos**

## Results and Visualization
The performance of the model was tested on different subsets of the dataset. Graphs for the sentiment analysis of 20, 50, and 100 videos are included in the `Graphs/` folder.
