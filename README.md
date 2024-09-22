# Ball-Tracking

## Short Description
Browser-based desktop app with integrated Computer Vision Object Detection to analyze student practice videos for cricket coaches. 
I personally collected training footage of myself bowling, annotated that cricket ball identification footage after splitting it into frames (with Roboflow CVAT). 
Used the annotated dataset as training data to train a Yolov8 detection model & set up a frame-by-frame division and inference process that recursively analyses any new footage entered into the platform.
Employed Flask web-framework with a python-based backend that uses PyTorch, Pandas and OpenCV2 for ML model inference and creating output videos/analysis features on new footage to be analysed by the platform.
Finally, I built the frontend with HTML/CSS & Javascript and packaged the frontend together with the flask-based backend using Jinjatemplates and app routing
Once I had built the application, I distributed a beta-release to cricket coaches of junior and senior cricket clubs around my state

### Detailed Description of Implementation
[Stage 1](https://github.com/AdityaGhai18/Ball-Tracking/blob/main/Documentation/Crit_A_Planning.pdf): Includes initial planning, formulating ideas, and coming up with success criteria
[Stage 2](https://github.com/AdityaGhai18/Ball-Tracking/blob/main/Documentation/Crit_B_Design.pdf): Includes Technical planning: 
- Design Diagrams
- GUI Diagrams
- Context Diagram
- Nav Diagram
- Computer Vision process flow
- App architecture diagrams
- Ball tracking video file handling diagram
- Flask Application Structure
[Stage 3](https://github.com/AdityaGhai18/Ball-Tracking/blob/main/Documentation/Crit_C_Development.pdf): Major product development and implementation, code snippets explained in detailed manner
[Stage 4](https://drive.google.com/file/d/1v97DqYsGUWnpTixgJwJ7fuQbDq-y9Hma/view?usp=sharing): Google drive link for demonstration and walk through video
[Stage 5](https://github.com/AdityaGhai18/Ball-Tracking/blob/main/Documentation/Crit_E_Evaluation.pdf): Evaluation based on 2-week beta testing period from cricket coaches 

