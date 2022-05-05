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
![YOLOharshoutput](https://user-images.githubusercontent.com/87551646/166853010-47f0916f-352a-4895-8e70-f092c8d6a52a.png)
![result1](https://user-images.githubusercontent.com/87551646/166853019-a88bf2b8-927f-4923-b572-c679863f085d.png)
![result2](https://user-images.githubusercontent.com/87551646/166853022-2a42241c-fbea-4f09-8400-efbfa6fcec74.png)



 For 3D reconstruction:
 1. open the google codab lin provided following or open the 3D Reconstruction.ipynb file provided in the folder. 
 https://colab.research.google.com/drive/1Soz2y6siPBn9r5JdQGLztQahDteq7EPS?usp=sharing
 2. follow the step by step instruction provided inside.
 3. make sure to upload the image from the folder called "human" from the above(10 images are there).
    there is folder called demo consist of all the models created from the images just to check after.
 4. use blander tool to view the 3D model of the reconstructed image.
 the link to downlaod latest blender software is: https://www.blender.org/download/
