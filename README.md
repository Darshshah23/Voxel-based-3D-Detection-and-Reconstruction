Object detection from Image:

1) Open Google colab 
2) upload object_detection file in google colab
3) After opening the object_detection file, go the the file
   icon on the left and drag and drop the following files into that:
	1) coco.name
	2) yolov3.cfg
	3) yolov3. weights (Download the weights from https://www.kaggle.com/datasets/shivam316/yolov3-weights)
	4) Images
4) Now run each cells one by one
5) First install Mediapipe, then import Library, After that load YOLO,
   make list of classes and load Network. Then run the define function and at the
   end load and read an image in which you want to detect.
6) you will get the output.

Now for 3d bouding box:

1)Run the cell for loading the image
2)Now run the cell to create Bounding Box around the object


live Object detection:

1)Open yolo.py and run the code 
 