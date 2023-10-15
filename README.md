# Traffic_Lights_Irregularity_Detection

Project done as part of Summer_Internship.

### Problem Statement:-

  Develop a Deep learning algorithm that can detect Irregularities/Malfunctions in Traffic lights through Video Classification. 



### Requirements of the model:-

  -> The algorithm should be able to accurately identify each stage of the traffic light(red, yellow, green) even in videos taken at a angle.
  
  -> The algorithm should be able to correctly determine whether the traffic lights have any kind of malfunctions.
  
  -> It should also have a low false positive rate, so that it does not generate too many unnecessary alerts.


### Technologies Used:-

  ->Deep Learning.

  ->OPEN CV (COMPUTER VISION).

  ->YoloV8 (Ultralytics).
  
  ->Convolutional Neural Networks (CNN).

  ->IPython.
  
  ->moviepy (MoviePy is a Python library for video editing: cutting, concatenations, title insertions, video compositing etc…)


### Model Used:-
   -> Yolov8 to detect frame by frame detection in videos to classify the Traffic Lights.

### Before and after training the model

<img width="605" alt="image" src="https://github.com/vamsikrisna54/Traffic_Lights_Irregularity_Detection/assets/114807260/5479f93b-8f86-4060-b972-b4afad230399">

### Confusion matrix of custom trained model:-

![image](https://github.com/vamsikrisna54/Traffic_Lights_Irregularity_Detection/assets/114807260/11f30c1a-df73-4783-8028-032eea4a407e)

### Accuracy and Loss curves after custom model training on yolov8

![image](https://github.com/vamsikrisna54/Traffic_Lights_Irregularity_Detection/assets/114807260/5ee4922f-a569-4e80-95a4-40959c973c84)


###  Output:-

output when no irregularities

classs=True

![image](https://github.com/vamsikrisna54/Traffic_Lights_Irregularity_Detection/assets/114807260/24024c4f-934f-454f-a376-5ef62c672e42)

output when irrgularity where yellow light is skipped

class=False

![image](https://github.com/vamsikrisna54/Traffic_Lights_Irregularity_Detection/assets/114807260/872a5470-9583-4448-8ef9-e022b2de491a)



