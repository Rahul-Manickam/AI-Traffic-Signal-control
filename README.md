## AI-Powered Traffic Management System

This project demonstrates a comprehensive approach to traffic management using computer vision. The system addresses key challenges like congestion estimation, emergency vehicle detection, and intelligent signal control.

### Features

1. **Video to Frames:** Extracts frames from traffic videos for further analysis.
2. **Camera Calibration:** Calibrates camera parameters for accurate object detection.
3. **Object Detection:** Employs YOLOv5 to detect vehicles and pedestrians in real-time.
4. **Congestion Estimation:** Quantifies traffic density based on detected vehicles and their sizes.
5. **Emergency Vehicle Detection:** Identifies emergency vehicles to prioritize their passage.
6. **Intelligent Signal Control:** Dynamically adjusts traffic signal timings based on real-time traffic density data.

### Getting Started

1. **Prerequisites:**
   - Python 3.x
   - OpenCV (`pip install opencv-python`)
   - PyTorch (`pip install torch torchvision`)
   - Ultralytics YOLOv5 (`pip install ultralytics`)
   - Other libraries listed in the code files

2. **Usage:**
   - **Prepare Data:**
     - Place your traffic videos in the appropriate folders.
     - Capture calibration images for camera calibration.
   - **Run Scripts:**
     - Follow the instructions in each code file to execute the different functionalities.

### Project Structure

- `video_to_frames.py`: Extracts frames from video.
- `camera_calibration.py`: Calibrates the camera.
- `object_detection.py`: Detects objects in images or video frames.
- `congestion_calculation.py`: Estimates congestion based on object detection results.
- `emergency_vehicle_detection.py`: Trains and runs a model to detect emergency vehicles.
- `signal_control.py`: Simulates an adaptive traffic signal system.
- `scenario_1.csv`: Sample density data for testing. 

![](/1.png)

### Future Enhancements

- Integrate with traffic cameras for real-time analysis.
- Implement more sophisticated signal control algorithms.
- Incorporate vehicle tracking for better congestion estimation.

