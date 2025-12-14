# Pedestrian-Human-Vehicle-Detection-YOLOv5
 Real-time pedestrian, human &amp; vehicle detection using YOLOv5. Custom dataset training with Roboflow data. Academic ML project for urban safety applications in autonomous systems. Includes full training/evaluation pipeline.

**Overview**

A real-time object detection system using YOLOv5 to detect pedestrians, humans, and vehicles. Developed as a Machine Learning course project at COMSATS University Islamabad.

**What We Did**

Trained YOLOv5 on custom annotated datasets from Roboflow

Implemented three-class detection: pedestrians, humans, and vehicles

Applied transfer learning from pre-trained COCO weights

Evaluated model performance using standard object detection metrics

**Method**

**Data Preparation:**
Collected and annotated images using Makesense.ai and LabelImg tools

**Model Training:**
Fine-tuned YOLOv5s with 100 epochs, batch size 16, image size 640×640

**Augmentation:**
Applied mosaic augmentation for improved generalization

**Evaluation:**
Assessed precision, recall, and mAP@0.5 metrics

**Applications**

Autonomous vehicle safety systems

Surveillance and traffic monitoring

Urban planning and pedestrian safety analysis
