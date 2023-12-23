# Real-Time Object Detection with OpenCV
![GitHub repo size](https://img.shields.io/github/repo-size/harshitdhamecha/objectdetection)

Welcome to the Real-Time Object Detection with OpenCV project! 🚀 This repository provides a Python script for performing real-time object detection using OpenCV and the MobileNet SSD (Single Shot MultiBox Detector) model. Whether you're a developer, researcher, or hobbyist, this project allows you to quickly set up and experiment with object detection in live video streams.

## Overview 📝

The script utilizes OpenCV, a powerful computer vision library, and MobileNet SSD, a lightweight deep learning model designed for real-time object detection. With just a few steps, you can set up the environment, run the script, and witness the detection of various objects in the live video feed.

## Getting Started 🛠️

### Prerequisites

- Python 3.x
- OpenCV
- imutils

### Installation 📦

1. **Clone the repository and navigate to the project folder:**

    ```bash
    git clone https://github.com/harshitdhamecha/objectdetection.git
    cd Real-Time-Object-Detection-With-OpenCV
    ```

2. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

### Usage ▶️

1. **Run the script:**

    ```bash
    python real_time_object_detection.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel
    ```

2. Press 'q' to exit the real-time object detection.

### Customization ⚙️

You can customize the script by adjusting the script parameters and fine-tuning the confidence threshold.

### Contributing 🤝

Contributions are welcome! Feel free to open an issue or submit a pull request.

### Acknowledgments 🙏

- The script uses the MobileNet SSD model for object detection.
- Special thanks to the OpenCV community.

### How to Run 🚀

**Step 1:** Create a directory on your local machine and navigate into it

```bash
mkdir ~/Desktop/opencv_project
cd ~/Desktop/opencv_project
```

**Step 2:** Clone the repository and navigate into the folder:
```bash
git clone https://github.com/your-username/Real-Time-Object-Detection-With-OpenCV.git
cd Real-Time-Object-Detection-With-OpenCV
```

**Step 3:** Install necessary libraries:
```bash
brew install opencv
pip install opencv-python opencv-contrib-python opencv-python-headless opencv-contrib-python-headless matplotlib imutils
```
Make sure to download and install OpenCV and OpenCV-contrib releases for OpenCV 3.3 or newer.

**Step 4:** List your video devices:
```bash
system_profiler SPCameraDataType | grep "^    [^ ]" | sed "s/    //" | sed "s/://"
```

**Step 5:** Start the video stream and real-time object detection:
```bash
python real_time_object_detection.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel
```

**Step 6:** For help on script arguments:
```bash
python real_time_object_detection.py --help
```

## References and useful links  📚
[MobileNet - SSD](https://github.com/chuanqi305/MobileNet-SSD)

[OpenCV GitHub](https://github.com/opencv/opencv)

[BlobfromImage Explanation](https://www.pyimagesearch.com/2017/11/06/deep-learning-opencvs-blobfromimage-works/)

[imutils GitHub](https://github.com/jrosebr1/imutils)


```vbnet

Feel free to customize it further based on your preferences!
```

