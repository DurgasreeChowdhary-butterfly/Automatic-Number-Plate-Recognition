# Automatic-Number-Plate-Recognition

Features

- **License Plate Detection:** Utilizes YOLO V8 for detecting license plates in images or video feeds.
- **Text Recognition:** Uses EasyOCR to read text from detected license plates.
- **Object Tracking:** Tracks detected license plates across frames.
- **Result Logging:** Saves recognized license plate numbers to a CSV file.

Installation

Prerequisites

- Python 3.x
- pip (Python package installer)

Libraries

Install the necessary libraries using pip:

```
pip install yolov8 easyocr opencv-python pandas numpy
```

Additional Dependencies

Ensure you have the YOLO V8 weights file and necessary models for EasyOCR. You can download these from their respective sources.

The system will start processing the video feed, detect license plates, recognize text, track objects, and save the results to `results.csv`.

Project Structure

- `main.py`: The main script to run the ANPR system.
- `utils.py`: Utility functions for processing.
- `requirements.txt`: List of dependencies required for the project.
- `README.md`: Project documentation.

 How It Works

1. **License Plate Detection:** YOLO V8 detects license plates in the input images or video frames.
2. **Text Recognition:** EasyOCR reads text from the detected license plates.
3. **Object Tracking:** Tracks the detected license plates across multiple frames.
4. **Result Logging:** Saves the recognized license plate numbers and timestamps to a CSV file.

Future Enhancements

- **Improved Accuracy:** Enhance detection and recognition accuracy using advanced techniques.
- **Database Integration:** Store results in a database for better management and retrieval.
- **Web Interface:** Develop a web-based interface for easy interaction with the system.
