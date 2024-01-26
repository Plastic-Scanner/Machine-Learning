# Machine learning model for Lasercut plastic

I made a machine learning model to identify the type of plastic used in a lasercutting enviroment.
It is trained on the following plastic types: PMMA, PET, PC, PS, and other.
Dataset trained on: https://raw.githubusercontent.com/Plastic-Scanner/data/main/data/20240126_LasercutPlastic/measurement.csv
it uses the firmware from this repo: https://github.com/Plastic-Scanner/ESP32-TensorFlow
the firmware is used to both collect the data, and to later interpret the data.

In this folder you can find the following files:
2024-01-26_meta_data.h - the meta data used to train the model
2024-01-26_notebook - the notebook used to train the model
2024-01-26_gesture_model.tflite - the tflite model that resulted from the notebook
2024-01-26_model.h - the arduino model that resulted from the notebook