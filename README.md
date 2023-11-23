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
Before you run the webapp, you should put the `example_model.onnx` to the `webapp` floder.
And then you can use this app on your local PC by running it in the following step:
```
  streamlit run application.py
```

### Online Available:
You can access our app via the following URL:
```
https://fracture-detection-yolo.streamlit.app/
```
The detailed code for this version is available on the branch web.
