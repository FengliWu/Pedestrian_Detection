# Pedestrian_Detection

## Description
This project is using improved YOLOv5s model to detect occluded pedestrian.

## Key Features
- Improved YOLOv5s model to enhance occluded object detection capabilities by embedding SE attention mechanisms and replacing SPP with SPP-Fast modules in backbone and adding specialized detection head for small objects
- Constructed and trained improved model in PyTorch based on dataset of 2,000+ images with occluded pedestrians
## Tech Stack
- Data Processing: Python - Pandas, Numpy
- Modeling: Python - PyTorch

## Project Structure
```
Pedestrian Detection
├── data/    # trajectory dataset
├── models/
├── runs/
├── utils/
├── venv/
├── src/
|   ├── detect.py   # detection
|   ├── export.py   # export model to other formats
|   ├── train.py    # train
|   └── val.py      # validate
├── requirements.txt
├── README.md
└── LICENSE  
```

Feel free to open issues and pull requests to contribute!