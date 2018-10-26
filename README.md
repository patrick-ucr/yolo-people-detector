# YOLO freezed graph for people detection

I trained these models, YOLO and Tiny YOLO, based on their version 2 to localize people in image frames using VOC dataset (choose only images including people) and Penn-Fudan pedestrain dataset. You can just push pb files to your tensorflow workspace and use it in your Android applications. Just change the model file locations in your main activity java and change TensorFlowYoloDetector.java for NUM_CLASSES = 1. There you go!
