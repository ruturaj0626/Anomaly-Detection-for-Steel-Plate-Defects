# Anomaly Detection for Steel Plate Defects

![Steel Plate Defects](https://github.com/ruturaj0626/Anomaly-Detection-for-Steel-Plate-Defects/blob/main/Anomaly%20Detection%20for%20Steel%20Plate%20Defects.png)

This repository presents a machine learning-based approach for detecting and classifying anomalies or defects in steel plates using a single Jupyter Notebook. The dataset used in this project comes from research conducted by Semeion, the Research Center of Sciences of Communication. The primary objective of this research was to accurately classify various types of surface defects in stainless steel plates, encompassing six potential defect categories along with an "other" category. The input vector consists of 27 indicators that roughly describe the geometric shape of the defect and its outline.

Please note that due to the research's commissioned nature, detailed information about the 27 indicators used as input vectors or the specific types within the six classes of defects is unavailable.

## Context

The dataset contains 34 fields, with the first 27 fields representing various characteristics related to steel plate faults observed in images. Unfortunately, additional information regarding these columns is not available. Here's a list of the first 27 columns:

- X_Minimum
- X_Maximum
- Y_Minimum
- Y_Maximum
- Pixels_Areas
- X_Perimeter
- Y_Perimeter
- Sum_of_Luminosity
- Minimum_of_Luminosity
- Maximum_of_Luminosity
- Length_of_Conveyer
- TypeOfSteel_A300
- TypeOfSteel_A400
- Steel_Plate_Thickness
- Edges_Index
- Empty_Index
- Square_Index
- Outside_X_Index
- Edges_X_Index
- Edges_Y_Index
- Outside_Global_Index
- LogOfAreas
- Log_X_Index
- Log_Y_Index
- Orientation_Index
- Luminosity_Index
- SigmoidOfAreas

The last seven columns represent one-hot encoded class labels. In other words, if a plate fault is classified as "Stains," there will be a '1' in the "Stains" column and '0's in the other columns. The seven class labels are:

- Pastry
- Z_Scratch
- K_Scratch
- Stains
- Dirtiness
- Bumps
- Other_Faults

## Usage

To use this project, follow the steps in the single Jupyter Notebook provided in this repository. The notebook contains sections for data preparation, model training, and analysis. 

## License

This project is licensed under the [MIT License](LICENSE).
