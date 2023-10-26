## YOLO for Fracture Detection App
### Prepare Folder

```
  git clone https://github.com/RuiyangJu/YOLOv8_CBAM_Fracture_Detection
  cd YOLOv8_CBAM_Fracture_Detection
```

### Envirement Preparation
```
  pip install -r requirements.txt
```

### Download
Use gdown to download the trained model from our GitHub:
```
  gdown https://github.com/RuiyangJu/YOLOv8_CBAM_Fracture_Detection/releases/download/Example_Model/example_model.onnx
```

### Run

```
  streamlit run application.py
```
