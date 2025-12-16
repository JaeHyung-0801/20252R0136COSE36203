# 20252R0136COSE36203

# Music Genre Classification (GTZAN)

This project explores music genre classification using audio features
extracted from the GTZAN dataset. We investigate segment-level and song-level
classification performance using classical machine learning models.

## Pipeline
- Feature extraction from 3-second audio segments
- Exploratory data analysis (EDA)
- Feature engineering
- Train-test split with leakage prevention
- Model training and evaluation

## Dataset
- GTZAN music genre dataset
- Audio is segmented into 3-second clips
- Pre-extracted features are stored as CSV files
- Main experiments use `features_3_sec.csv` due to larger sample size

## Audio Features
- MFCC (1–13): timbre-related features
- Spectral features (centroid, bandwidth, rolloff)
- Zero-crossing rate
- Chroma and harmony statistics when available

## Feature Selection
We select features that are known to be effective for music genre classification:
- MFCC (1–13): timbre-related information
- Spectral features: centroid, bandwidth, rolloff
- Zero Crossing Rate: rhythmic/noise characteristics

