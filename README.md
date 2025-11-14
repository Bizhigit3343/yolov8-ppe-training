# YOLOv8 PPE Training (Helmet, Vest, Person)

Custom dataset + training pipeline for building a PPE detection model (Hard Hat, Safety Vest, Person), used in the SAQ (Safe Vision Core) system.

Includes:
- dataset structure  
- training script  
- ready-to-run YOLO commands  
- export to ONNX / TensorRT  

---

## 🚀 Training command

```bash
yolo detect train model=yolov8n.pt data=data/dataset.yaml epochs=100 imgsz=640 batch=16
