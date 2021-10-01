# Recognizing Book Signatures using a Mobile RGB-Camera

This repository contains the complete code for the recognition of book signatures using a mobile RGB Camera. Code is provided in Jupyter notebooks. The detection and recognition is currently trained on the format used by the library of the University of Applied Sciences W ̈urzburg-Schweinfurt. The used standard is "Regensburger Verbundklassifikation (RVK)".


## Hardware Requirements

- Implementation was performed on Google Colab instances
- GPU acceleration is recommended (strictly required by YOLOv4, otherwise optional)
- RGB-Camera (Smartphone)


## Dependencies

- Python 3.7
- Individual dependencies required in addition to Google Colab preinstalled modules are reported in the Jupyter notebooks
- requirements.txt can be used as reference, if no Google Colab instance is used for execution


## Repository Structure

- **evaluation:** Contains evaluation notebooks for run time and accuracy analysis of Object Detection (OD) and Optical Character Recognition (OCR). Subfolder *tools* does reference repositories used for evaluation.
- **signature_detection:** Contains implemented OD solutions for book signature detection. Subfolder training contains notebooks to train each individual detector on personal data sets
- **signature_recognition:** Contains implemented OCR solutions for book signature recognition.


## Models

For object detection, models or weight files are needed. Pretrained models can be found [here](https://drive.google.com/drive/folders/1kdak4UZxd0ImufVfAoJ9BbI3jzYkjzVy?usp=sharing)


## Data set

The data used for this work is not publicly available. Please contact <kontakt@leon-heller.com> for requests.
