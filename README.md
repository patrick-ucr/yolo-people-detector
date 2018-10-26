# YOLO freezed graph for people detection on Android

I trained these models, YOLO and Tiny YOLO, based on their version 2 to localize people in image frames using VOC dataset (choose only images including people) and Penn-Fudan pedestrain dataset. You can just push pb files to the Android's asset folder and use it in your Android applications. Just change the model file locations in your main activity java and change TensorFlowYoloDetector.java for NUM_CLASSES = 1. There you go!

YOLO: https://www.dropbox.com/s/b7w9qewubnmvupt/yolo-people.pb?dl=0

Tiny YOLO: https://www.dropbox.com/s/9cldbrxf2kn6on4/tiny-yolo-people.pb?dl=0
