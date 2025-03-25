BCCD Object Detection

BCCD Object Detection is a deep learning-based project for detecting blood cell types (RBC, WBC, Platelets) using YOLOv10. The model is trained on the BCCD dataset and deployed using Hugging Face Spaces.

Features

->Detects Red Blood Cells (RBC), White Blood Cells (WBC), and Platelets.

->Uses YOLOv10 for object detection.

->Web app built with Gradio for easy image upload and detection.

->Deployed on Hugging Face Spaces.

Dataset Structure

BCCD_Dataset/
│── BCCD/
│   ├── Annotations/  # XML files
│   ├── JPEGImages/   # Raw images
│   ├── ImageSets/Main/  # Train/Test splits
│── images/
│   ├── train/
│   ├── val/
│── labels/
│   ├── train/
│   ├── val/
│── test.csv

