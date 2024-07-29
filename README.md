# 🚦 TrafficVision: Real-Time Density Analysis with YOLOv8

TrafficVision is a real-time traffic density estimation application using the YOLOv8 object detection model. This project provides a robust solution for analyzing traffic conditions by processing video inputs and estimating vehicle density in different lanes.

## 🛠️ Features

- 📹 **Real-Time Traffic Analysis**: Processes video inputs to detect vehicles and analyze traffic density.
- 🚗 **Lane-Specific Density Estimation**: Counts vehicles in specific lanes and determines traffic intensity.
- 🎥 **Video Processing**: Converts and processes video files, displaying results with annotated vehicle counts and traffic intensity.

## 📂 Project Structure

- `app.py` - Streamlit application code for uploading, processing, and displaying videos.
- `traffic_density_estimation.py` - Core logic for video processing and vehicle detection.
- `models/` - Directory containing YOLOv8 model weights and configurations.
- `data/` - Sample videos and datasets used for testing.
- `requirements.txt` - List of required Python packages for the project.
- `README.md` - This README file.

## 📦 Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/TrafficVision.git

2. **Navigate to the project directory**:
   ```bash
    cd TrafficVision

3. **Create and activate a virtual environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   
4. **Install the required packages**:
    ```bash
    pip install -r requirements.txt

## 📝 Usage

1. **Run the Streamlit application**:
   ```bash
   streamlit run app.py

2. Upload a video file: Use the Streamlit interface to upload a video in MP4 or AVI format.

3. View the results: The processed video with annotated vehicle counts and traffic intensity will be displayed.

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for more details.

## 🤝 Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request with your changes. For more information, refer to the CONTRIBUTING guidelines.

## 📝 Acknowledgements
- YOLOv8 for object detection.
- Streamlit for the user interface.


