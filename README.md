# Transformer_Fall_Detection
Transformer-based fall detection system using multi-sensor data
Transformer-Based Fall Detection System Using Multi-Sensor Data
Description
This repository contains the full implementation of a Transformer-based fall detection system leveraging multi-sensor fusion (accelerometer, gyroscope, magnetometer) for Parkinson's Disease (PD) patients. The system aims to detect falls, particularly during Freezing of Gait (FoG) episodes, with high accuracy.

Features
Preprocessing Scripts: Includes data cleaning, scaling, and feature extraction from multi-sensor data.
Transformer Model Implementation: Utilizes a multi-head self-attention mechanism for analyzing temporal motion data.
Training and Evaluation: Scripts for training the model on benchmark datasets and evaluating the performance using key metrics like accuracy, precision, recall, and F1 score.
Visualizations: Tools to generate and save confusion matrices, feature correlation heatmaps, and model performance comparison charts.
Datasets
The system has been validated on the following datasets:

Daphnet
SisFall
UP-Fall
System Requirements
Python: 3.6 or higher
Required Libraries: Listed in the requirements.txt file
Example: tensorflow, scikit-learn, seaborn, etc.

To install the dependencies, run:
pip install -r requirements.txt

Setup Instructions
Clone the repository: git clone https://github.com/Farjana-Yesmin/Transformer_Fall_Detection.git
cd Transformer_Fall_Detection

Install dependencies:
pip install -r requirements.txt

Prepare datasets:
The system has been validated on three datasets:

Daphnet: (https://drive.google.com/file/d/16L3aDa1c2mv943xo6oJivhWALKptCOAC/view?usp=sharing)
SisFall: (https://drive.google.com/drive/folders/1MgnbkdZUHERyWrk_UqgdW-o9M7wB8n5r?usp=sharing)
UP-Fall: (https://drive.google.com/file/d/1-KMMKvFCk6uez5JGHtNvplo14SOAnMCE/view?usp=sharing)
Download the datasets using the links above.

Please follow the instructions in the datasets/README.md to make sure that you have the correct formatting and data structure.
Run preprocessing:

The preprocessing scripts will clean and format the data for the model.
python data_preprocessing/preprocess.py

Train the model:

This will start the training process using the preprocessed data.
python training/train.py
Generate visualizations:

Once the model is trained, you can generate confusion matrices and other performance plots.

python visualizations/confusion_matrix_plot.py

Results and Visualizations:
The confusion matrix, feature correlation heatmap, and model performance comparison charts will be saved in the visualizations/ folder.

Example output images can be found in the example_output/ subfolder.

License:
This project is licensed under the MIT License - see the LICENSE file for details.

Contributors:
Farjana Yesmin
