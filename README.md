## Deep troll (Gemidao do Whatsapp) detector

Tired of getting caught on difficult situations after playing some Whatsapp content with a troll in it?

Let's put deep learning to work for the good!

Deep troll uses a deep learning model that identifies whether an audio contains the Gemidao troll (AAAWN OOOWN NHAAA AWWWWN AAAAAH).

The model uses a RNN-GRU arquitecture, using covolutions on audio spectograms to extract features.

## Setup

1. Use the `requirements.txt` file to install the dependencies (preferably using virtualenv)

```
git clone https://github.com/andriosr/deeptrolldetector.git
cd deeptrolldetector
virtualenv deeptroll_env
source deeptroll_env/bin/activate
pip install -r requirements.txt
```

2. Download the training set and pre-trained models at:
```
https://drive.google.com/file/d/1wBfrJ7UPC0BLJZlJRlSZgSHxC_YButiF
```

3. Extract the downloaded file in the project folder, setting its name to `data`

4. Start Jupyter, open the `Deep_Trool_Detector.ipynb` and let the fun begin

```
jupyter notebook
```