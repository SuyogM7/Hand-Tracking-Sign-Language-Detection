# Hand Tracking Sign Language Detection

## Project Overview
This project is a hand tracking-based system for detecting and interpreting sign language gestures. Using computer vision and machine learning, the project captures hand movements and processes them to recognize specific sign language gestures. The project is divided into three main components: capturing hand movements, gathering and labeling data, and testing the trained model for gesture recognition accuracy.

## Project Structure
- **Hand Movement Capture** (`Hand Tracking Software.py`): This module captures real-time hand movements using a webcam. It processes hand landmarks to extract relevant features for gesture recognition.
  
- **Data Collection** (`Data Collection.py`): This module is responsible for capturing and storing data for different sign language gestures. Each gesture is labeled and stored to create a dataset, which is then used for training the model.

- **Testing and Recognition** (`testing.py`): This module loads the trained model and evaluates its performance by recognizing gestures in real time. The accuracy of each prediction is displayed, providing a measure of model effectiveness.

## Key Features
- **Real-time Hand Tracking**: Uses computer vision techniques to identify and track hand landmarks, providing consistent input for gesture detection.
- **Gesture Recognition**: Classifies hand movements into corresponding sign language gestures.
- **Data Collection and Model Testing**: Includes tools for data collection, model training, and testing for gesture recognition accuracy.

## Usage
1. **Setup**: Ensure all required libraries are installed (OpenCV, Mediapipe, etc.).
2. **Capture Hand Movements**: Run `capture_hand_movements.py` to start capturing and processing hand movements.
3. **Data Collection**: Use `data_capture.py` to gather and label gestures for training the model.
4. **Testing**: Run `test_model.py` to evaluate model performance on real-time gesture recognition.

## Technologies Used
- **Python**: Core programming language for hand tracking, data collection, and model testing.
- **OpenCV**: For real-time video capture and processing.
- **Mediapipe**: For hand landmark tracking.
- **Machine Learning Model**: Used for recognizing and classifying hand gestures in sign language.

## Summary
This project demonstrates a computer vision approach to detecting sign language gestures through hand tracking. The system captures, processes, and recognizes gestures, offering a foundation fo
