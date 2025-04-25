# rf-detr parking-lot-detection
# Parking Lot Detection with RFDETR
This repository demonstrates an end-to-end pipeline for detecting parking lots using the [RFDETR](https://github.com/roboflow-ai/rfdetr) object detection model, trained on a custom dataset exported from Roboflow in COCO format. It includes distributed training support via PyTorch's `torchrun`, prediction visualization, and usage examples.
---
## 📦 Dataset
- **Name:** Parking Lot Detection YOLOv-12  
- **Source:** [Roboflow Universe](https://universe.roboflow.com/harshavardhan-adefc/parking-lot-detection-yolov-12)  
- **License:** CC BY 4.0  
- **Annotations:** COCO format  
- **Size:** 14,610 images  
- **Preprocessing:**  
  - Auto-orientation and EXIF stripping  
  - Resize to 640x640  
- **Augmentations:** 3 versions per image
Kaggle dataset link: [View on Kaggle](https://www.kaggle.com/datasets/kandatiharshavardhan/parking-lot-detection-coco)
---
## 🧰 Dependencies
```bash
pip install torch torchvision
pip install supervision
pip install rfdetr
