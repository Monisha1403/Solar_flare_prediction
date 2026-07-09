# 🌞 Solar Flare Prediction

## Overview

Solar Flare Prediction is a deep learning-based application that predicts the likelihood of solar flare events using solar magnetogram images and solar activity data. The project combines image processing, Convolutional Neural Networks (CNNs), and a Streamlit interface to provide an interactive prediction system.

---

## Objectives

- Predict solar flare occurrences using deep learning.
- Improve prediction reliability using multiple scientific datasets.
- Provide an easy-to-use web interface for prediction.

---

## Features

- Solar flare prediction using CNN
- Magnetogram image processing
- Real-time prediction through Streamlit
- Model performance visualization
- Scientific dataset integration

---

## Technology Stack

- Python
- TensorFlow
- OpenCV
- NumPy
- Pandas
- Streamlit

---

## Dataset

- JSOC Solar Magnetogram Dataset
- NOAA Solar Activity Dataset

---

## Project Workflow

1. Collect magnetogram images.
2. Preprocess images.
3. Train the CNN model.
4. Evaluate model accuracy.
5. Deploy using Streamlit.
6. Predict solar flare probability.

---

## Repository Structure
Solar-Flare-Prediction/ │── app.py │── model/ │── dataset/ │── images/ │── Solar_Flare_Prediction.pptx │── requirements.txt │── README.md

---

## Installation

```bash
git clone <repository-url>

cd Solar-Flare-Prediction

pip install -r requirements.txt

streamlit run app.py
