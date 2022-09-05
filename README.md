# Freesound-Audio-Tagging
Freesound General-Purpose Audio Tagging Kaggle Competition.

## Description
The objective of this competition was to predict the category of an audio clip from a subset of 41 diverse categories drawn from Audioset Ontology. LightGBM model was trained to classify the categories and MAP@K was used as an evaluation metric for this competition.

## Dataset
The dataset of this competition can be easily found at <a href="https://www.kaggle.com/competitions/freesound-audio-tagging/data" target="_blank">Kaggle Dataset</a>. The FSDKaggle2018 contains a total of 11,073 files provided as uncompressed PCM 16 bit, 44.1 kHz, mono audio files.

### Google Colab setup with Dataset
<ol>
  <li> Download your API token from your Kaggle Profile section. A file named 'Kaggle.json' will be downloaded.
  <li> Set up your colab notebook by uplaoding the kaggle.json file. Then exceute the following commands.
</ol>

   ```
    ! pip install -q kaggle
    ! cp kaggle.json ~/.kaggle/
    ! chmod 600 ~/.kaggle/kaggle.json
    ! kaggle competitions download freesound-audio-tagging
    ! unzip freesound-audio-tagging.zip
    ```

## Acknowledgment
https://www.youtube.com/watch?v=3CtPuwok7Nw&list=PL6r4_rPnd1bJsepeF3T2txtbSXv01pFY4
