# Facemask-Detector
Real-time Facemask Detection using MobileNetv2-SSD model and Object Detection API

# About Project
This project uses a Deep Neural Network model called "ssd_mobilenet_v2_320x320_coco17_tpu-8" (from TensorFlow model zoo) and TensorFlow's Object Detection API to build a model that can detect a person's face and to classify whether it has a mask on it or not. This detector is trained by using only 194 images and gives a descent accuracy in detection. By using OpenCV, this trained model can perform a real-time face mask detection with almost zero lag. The video from the webcam will be pre-processed frame-by-frame and fed to the detector. The output from the detector is then post-processed and will give out to the display.

The model can detect and do prediction of multiple faces at the same time.

# Working

With Mask

![alt text](https://github.com/sebastianmathai/Facemask-Detector/blob/main/mask.png)

Without Mask

![alt text](https://github.com/sebastianmathai/Facemask-Detector/blob/main/no_mask.png)


# Steps to use this project

1. Clone this repository on to the system:

       git clone https://github.com/sebastianmathai/Facemask-Detector.git

2. Navigate to the directory:

       cd Facemask-Detector
        
4. Download the necessary libraries:

(*Hint: Install Jupyter Notebook before this step if not already available in your system*)

       pip install -r requirements.txt
      
4. Open Jupyter Notebook
5. Run the notebook "object_detection_live.ipynb"
## Now the project is ready to use and can experience a real-time detection of the facemask by using the webcam
