# Remote Accident Detection System  

A real-time accident detection system that leverages deep learning to identify and respond to accidents efficiently. This project utilizes TensorFlow for model training, OpenCV for video processing, and a pre-trained model for predictions.

## Features  

- Accurate Predictions: Uses a trained deep learning model to classify frames as "Accident" or "No Accident."  
- Video Processing: Processes video footage in real-time using OpenCV.  
- Scalable Design: Designed for easy integration into larger safety systems.  
- Alert Mechanism: Provides alerts based on the probability of an accident.  

## Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-repo/accident-detection-system.git  
   cd accident-detection-system  
   ```

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt  
   ```

3. Place the required files:   
   - `demovid.mp4`: Input video for demo.  

## Usage  

1. Run the application:  
   ```bash
   python main.py  
   ```  

2. Press `q` to quit the application during video playback.  

## Project Structure  

```
├── main.py          # Entry point to start the application  
├── demo.py          # Handles video processing and predictions  
├── model.py         # Loads the model and predicts accidents 
├── demovid.mp4      # Sample video for testing
├── code.ipynb       # Training the model and evaluating accuracy scores
├── requirements.txt # Python dependencies  
```

## License  

This project is licensed under the MIT License - see the LICENSE file for details.
