
# Projects Overview

This repository contains two projects: a Text-to-Speech (TTS) project using Microsoft's SpeechT5 model and a YOLO Object Detector project using the YOLOv5 model. 

## Text-to-Speech Project

### Description

This project demonstrates the use of the Microsoft SpeechT5 model for text-to-speech synthesis. It provides examples of generating speech from text using pre-trained models and speaker embeddings.

### Requirements

- `torch`
- `transformers`
- `datasets`
- `soundfile`

Install the required packages using:

```bash
pip install torch transformers datasets soundfile
```

### Usage

1. **Initialize the TTS pipeline:**
   - Use the `pipeline` function from `transformers` to create a text-to-speech pipeline with the `microsoft/speecht5_tts` model.

2. **Load speaker embeddings:**
   - Load speaker embeddings from the `Matthijs/cmu-arctic-xvectors` dataset.

3. **Generate and save speech:**
   - Generate speech from text and save it as an audio file.

### Example Commands

1. Initialize the pipeline and synthesizer.
2. Load the embeddings dataset and extract a specific embedding.
3. Generate speech and save it to a file.

### License

This project is licensed under the MIT License.

## YOLO Object Detector Project

### Description

This project demonstrates the implementation of the YOLOv5 object detection model. It provides examples of loading the model, preprocessing images, performing object detection, and visualizing the results.

### Requirements

- `torch`
- `opencv-python`
- `matplotlib`
- `yolov5` (from the official YOLOv5 repository)

Install the required packages using:

```bash
pip install torch opencv-python matplotlib git+https://github.com/ultralytics/yolov5.git
```

### Usage

1. **Load the YOLOv5 model:**
   - Load the pre-trained YOLOv5 model using the `torch.hub.load` method.

2. **Preprocess images:**
   - Preprocess input images to the required format for YOLOv5.

3. **Perform object detection:**
   - Use the model to detect objects in the preprocessed images.

4. **Draw bounding boxes and visualize results:**
   - Draw bounding boxes around detected objects and display/save the result.

### Example Commands

1. Load and preprocess an image.
2. Perform object detection and apply non-max suppression.
3. Draw bounding boxes on detected objects and display/save the resulting image.


## Contributing

