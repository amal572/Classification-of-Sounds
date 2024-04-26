# Classification of Sounds - Machine Learning Project
In this project aimed at classifying various sounds (specifically breaking glass and shooting sounds), I utilized the ESC-50 dataset. You can download it from [here]([link_to_dataset](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset). However, since the ESC-50 dataset does not include shooting sounds, I collected additional sound files, resulting in 532 wave files for analysis.

## Methodology

### Feature Extraction
Extracted features from the audio encompassed both time domain features (zero crossing rate, short-term energy) and frequency domain features (short-term entropy of energy, spectral centroid and spread, spectral entropy, spectral flux, spectral roll-off, and the first 13 features from MFCCs).

### Statistical Summary
We calculated the median and absolute deviation for all windows within each sound file.

### Modeling
We employed various machine-learning models for sound classification. Following data preparation and visualization, the best-performing model, Gradient Boosting, was selected for final classification.

## Repository Structure
- **/data**: Contains the ESC-50 dataset and additional sound files collected.
- **/scripts**: Includes scripts for feature extraction, data preparation, model training, and evaluation.
- **/models**: Stores trained models, particularly the Gradient Boosting model.
- **/results**: Holds evaluation metrics, classification reports, and visualizations.

## Requirements
- Python 3.x
- Required Python libraries (seaborn, pandas, NumPy, SciPy, scikit-learn, Librosa)


