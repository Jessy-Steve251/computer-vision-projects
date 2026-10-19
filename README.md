# Computer Vision Projects

Applied computer-vision work in PyTorch and YOLO — object detection, training pipelines, and real-time detection-and-alert systems. Each notebook tackles a distinct problem end to end, from data preparation to evaluation.

## Projects

### `object_detection_training_pipeline.ipynb`
A full custom object-detection training pipeline: PyTorch `Dataset`/`DataLoader`, Albumentations augmentation, model training and evaluation, with artifacts handled via AWS (boto3). Demonstrates the complete lifecycle of building a detection model on a custom dataset rather than only running inference.

### `yolov8_motion_landmark_detection.ipynb`
YOLOv8 applied to video: frame-by-frame detection with object tracking (frame buffering) and signal processing over the detected series. Built to turn raw footage into structured, analysis-ready outputs.

### `weapon_detection_alert_system.ipynb`
A security use case (aligned with SDG 16): YOLO + OpenCV detect threats in a video stream and trigger an automated email alert on detection. An end-to-end "detect → decide → notify" loop, not just a model.

## Stack
Python · PyTorch · Ultralytics YOLO / YOLOv8 · OpenCV · Albumentations · NumPy

## Notes
Model weights and video data are not committed (see `.gitignore`); each notebook documents the data it expects. Notebooks were developed in Google Colab.
