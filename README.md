# Hand_Detection
Hand Detection using OpenCV and mediapipelines

**MediaPipe** is a framework mainly used for building audio, video, or any time series data. With the help of the MediaPipe framework, we can build very impressive pipelines for different media processing functions.

Some of the major applications of MediaPipe.

Multi-hand Tracking
Face Detection
Object Detection and Tracking
Objectron: 3D Object Detection and Tracking
AutoFlip: Automatic video cropping pipeline etc.

Basically, the MediaPipe uses a single-shot palm detection model and once that is done it performs precise key point localization of 21 3D palm coordinates in the detected hand region.

The MediaPipe pipeline utilizes multiple models like, a palm detection model that returns an oriented hand bounding box from the full image. The cropped image region is fed to a hand landmark model defined by the palm detector and returns high-fidelity 3D hand key points.
