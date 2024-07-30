# Real-Time T-Shirt Color Detection Using YOLOv8

## 📋 Project Overview

This project demonstrates a real-time T-shirt color detection system using the YOLOv8 object detection model. The system captures video frames from a webcam feed, detects T-shirts in the frame, and classifies their colors. The detected T-shirts are highlighted with bounding boxes and labeled with the detected color and confidence score.

## ✨ Features

- **Real-Time Detection**: Captures and processes video frames in real-time using a webcam.
- **YOLOv8 Model**: Utilizes YOLOv8 for fast and accurate object detection.
- **Color Classification**: Identifies and classifies T-shirt colors into predefined categories (black, blue, grey, white).
- **Bounding Box Visualization**: Displays bounding boxes around detected T-shirts with color labels and confidence scores.

## 🛠️ Tools and Technologies

- **YOLOv8**: State-of-the-art object detection model.
- **OpenCV**: Library for image and video processing.
- **Matplotlib**: Visualization library for displaying results.
- **Google Colab**: Cloud-based environment for running the project with GPU support.

## 🚀 Installation

To set up this project locally, follow these steps:

1. **Clone the Repository:**
    ```bash
    git clone [https://github.com/AbdulRehman-git/real-time-tshirt-color-detection.git](https://github.com/AbdulRehman-git/real-time-tshirt-color-detection-yolov8.git)
    cd real-time-tshirt-color-detection
    ```

2. **Install Dependencies:**
    Make sure you have Python installed, then install the required libraries:
    ```bash
    pip install ultralytics opencv-python-headless matplotlib
    ```

3. **Upload the YOLOv8 Model:**
    Ensure the YOLOv8 model file (`tshirt_detection_model.pt`) is in the project directory or specify the correct path in the notebook.

## 🏗️ Usage

1. Open the notebook `Tshirt_Color_Detection.ipynb` in Google Colab or a local Jupyter environment.
2. Run the cells to install the required packages and configure the YOLOv8 model.
3. Execute the cells to start capturing video from the webcam and detecting T-shirt colors in real-time.

## 📝 Notes

- Make sure your webcam is connected and accessible.
- Adjust model paths and parameters as needed.
- The project is optimized for use in Google Colab, but can be adapted for local environments.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [YOLOv8](https://github.com/ultralytics/yolov8) for the object detection model.
- [OpenCV](https://opencv.org/) for the image processing library.
- [Matplotlib](https://matplotlib.org/) for visualization support.
- [Google Colab](https://colab.research.google.com/) for providing a cloud-based environment.

## 📧 Contact

For questions or suggestions, please contact 
- [![Email](https://img.shields.io/badge/Gmail-Contact-red)](mailto:inboxx.abdulrehman@gamil.com)
  - Feel free to reach out via email at inboxx.abdulrehman@gamil.com.
- [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](http://www.linkedin.com/in/abdul-rehman-052292271)
  - Connect with me on LinkedIn for professional updates and discussions.
- [![Twitter](https://img.shields.io/badge/Twitter-Follow-blue)](https://twitter.com/AbdulRehman_twt)
  - Follow me on Twitter for the latest in data science trends and insights.

