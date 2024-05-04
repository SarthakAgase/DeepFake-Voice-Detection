# DeepFake Voice Detection

DeepFake Voice Detection (Voice Auth) is a deep-learning project aimed at audio verification, particularly focused on distinguishing between deepfake and original audio files. Deepfake technology poses significant challenges to audio authentication, and this project leverages machine learning techniques to address this issue.

## Project Overview
The project employs various machine learning algorithms to analyze audio features extracted from both deepfake and original audio files. These features include:

- 20 Mel-Frequency Cepstral Coefficients (MFCC)
- Spectral Centroid
- Spectral Bandwidth
- Spectral Roll-off
- Zero Crossing Rate
- Chromagram Short-Fourier Transform

## Methodology
1. Data Collection and Preprocessing:
   - Deepfake and original audio samples were collected from diverse sources.
   - Audio preprocessing was performed to extract relevant features using the librosa library in Python.
2. Feature Extraction:
   - Audio features were extracted using the librosa library, including MFCC, spectral centroid, spectral bandwidth, spectral roll-off, zero crossing rate, and chromagram short-Fourier transform.
3. Model Training:
   Various classification models were trained on the extracted features to detect deepfake audio. The models employed include:
   - MLPClassifier
   - GradientBoostingClassifier
   - LGBMClassifier
   - CatBoostClassifier
   - XGBClassifier
   - ExtraTreesClassifier
   - RandomForestClassifier
   - DecisionTreeClassifier
   - LogisticRegression
   - SVC
   - KNeighborsClassifier
   - GaussianNB
   - AdaBoostClassifier
4. Model Evaluation:
   - The trained models were evaluated using appropriate evaluation metrics to assess their performance in distinguishing between deepfake and original audio files.

## Usage
1. **Requirements:**
   - Python 3.x
   - Required libraries: librosa, scikit-learn, lightgbm, catboost, xgboost
2. **Installation:**
   - Clone the repository to your local machine:
     ```bash
     git clone https://github.com/SarthakAgase/DeepFake-Voice-Detection
     ```
   - Install the required libraries:
     ```bash
     pip install -r requirements.txt
     ```
3. **Usage:**
   - Run the main.py script to execute the entire pipeline, including data preprocessing, feature extraction, model training, and evaluation.
     ```bash
     python main.py
     ```

## Results
   - Detailed results, including model performance metrics and evaluation summaries, can be found in the project's documentation or result files.

## Contributing

Contributions are always welcome!

If you find any issues or have suggestions for improvement, please submit an issue or create a pull request. Make sure to follow the project's code of conduct.

## Contact
For any inquiries or questions, feel free to contact the project maintainers at sarthak.agase@gmail.com
