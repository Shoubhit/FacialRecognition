# FacialRecognition
This repository contains a simple Python script for real-time face detection using the OpenCV library. The script captures video from your computer's webcam and detects faces in each frame, drawing rectangles around them.

## Customization
You can modify the script to fit your needs:

### Change the classifier: 
OpenCV provides other pre-trained classifiers for different objects like eyes, smiles, etc. You can replace the haarcascade_frontalface_default.xml with a different classifier XML file.

### Adjust the detection parameters: 
You can fine-tune the face detection by changing the parameters in the detectMultiScale function. The second and third arguments control scaling and the number of neighbors, respectively. Experiment with these values to optimize detection for your specific use case.
