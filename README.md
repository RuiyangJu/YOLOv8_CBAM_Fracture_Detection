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
  gdown https://github.com/RuiyangJu/x-ray_fracture_detection_yolo/releases/download/Example_Model/example_model.onnx
```

### Run
You can use our app on your local PC by running it in the following step:
```
  streamlit run application.py
```

### Online Available:
You can access our app via the following URL:
```
https://fracture-detection-yolo.streamlit.app/
```
The detailed code for this version is available on the branch web.
