# RenAI: Handwritten Text Recognition for Renaissance Spanish Manuscripts

## Project Overview

RenAI is a deep learning-based project aimed at recognizing handwritten text in Renaissance Spanish manuscripts. This project utilizes advanced image processing techniques and neural networks to convert scanned manuscript pages into human-readable text.

## Features

- PDF to image conversion
- Image preprocessing and segmentation
- Text detection using CRAFT (Character Region Awareness for Text Detection)
- Word extraction and normalization
- Handwritten text recognition


## Project Structure

- `preprocessing/`: Contains scripts for PDF to image conversion and image preprocessing
- `CRAFT/`: Text detection model
- `testing_data1/` and `testing_data2/`: Directories for processed word images
- `utils.py`: Utility functions for image processing and data handling

## Data Processing Pipeline

1. Convert PDF to images
2. Preprocess images (binarization, noise removal)
3. Detect text regions using CRAFT
4. Extract individual words
5. Normalize word images
6. Perform text recognition on test images

## Model Architecture

The project uses a combination of:

- CRAFT for text detection
- Custom CNN + RNN architecture for historical sclupture text recognition


## Model Performance
| Metric | Value |
|--------|-------|
| Character Accuracy | 1.0 |
| CER | 0.0 |
| CTC Loss | 0.2579 |
| Validation Loss | 0.0364 |

