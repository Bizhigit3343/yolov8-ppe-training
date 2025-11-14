# YOLOv8 PPE Training (Helmet, Vest, Person)

Custom dataset + training pipeline for building a PPE detection model.

## Train
yolo detect train model=yolov8n.pt data=data/dataset.yaml epochs=100 imgsz=640 batch=16

## Export
yolo export model=runs/detect/train/weights/best.pt format=onnx
