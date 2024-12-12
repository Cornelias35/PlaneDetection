# PlaneDetection
I used public dataset about planes which can be found from Kaggle: https://www.kaggle.com/datasets/nelyg8002000/commercial-aircraft-dataset .
I used first 200 images from dataset and annotated with CVAT. After annotation, I configured config.yaml to path train dataset. I run with 30 epochs for train and test it with test_detection.iypnb.

## Technologies:
- Yolo11 for model train
- OpenCV for video read
- CVAT for data annotation

## To use:
- Download Yolo and OpenCV to python environment.
- Correct the paths that inside in config.yaml and train_model.ipynb.
