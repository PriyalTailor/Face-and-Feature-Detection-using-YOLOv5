# Face-and-Feature-Detection-using-YOLOv5
This project implements **face and facial feature detection** using a custom YOLOv5 object detection model.

## Project Overview
- **Model:** YOLOv5 object detection
- **Input Image Size:** 320x320
- **Accuracy Achieved:** 97%
- **Dataset:** Custom dataset of 143 images (single and multi-face images)  
  *Dataset is private and not included in this repo.*

  ## Workflow
  <img width="2752" height="1455" alt="FaceAndFeatureDetectionWithYOLO" src="https://github.com/user-attachments/assets/c7811304-c519-4a20-a7c5-1851e48b598e" />

  **Steps:**
1. Dataset creation and labelling using [Make Sense AI](https://makesense.ai/).  
2. Bounding boxes stored in YOLO format:
   - Class number
   - Standardized center coordinates (x, y)
   - Standardised width & height
3. Set up YOLOv5 environment and directories.  
4. Configure YAML files for training.  
5. Train the YOLOv5 model.  
6. Detect faces and features on test images.

## Sample Results
![SingleFaceResults](https://github.com/user-attachments/assets/9fcc7b35-b9a8-40fb-895f-d98405a9137e)
*Sample results showing YOLOv5 detecting a single face with a bounding box and features highlighted.*

### Multi-face detection
![MultiFaceResults](https://github.com/user-attachments/assets/416eb346-9ca7-4474-a183-3b0b11f4e3d2)
*Sample results showing YOLOv5 detecting multiple faces in an image with bounding boxes and features highlighted.*


## How to run
1. Clone the repository:
   ```bash
   git clone https://github.com/PriyalTailor/Face-and-Feature-Detection-using-YOLOv5
Run the notebook or scripts. Note: The dataset is private, so training requires your own images.

## Acknowledgements
- [YOLOv5](https://github.com/ultralytics/yolov5)
- [Make Sense AI](https://www.makesense.ai/) - For Annotation
