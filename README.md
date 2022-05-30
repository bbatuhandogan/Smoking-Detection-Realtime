# Smoking-Detection-Realtime
Abstract-- The study was carried out to detect harmful content related to cigarette or drug use, which can
be encountered by younger individuals in the virtual environment due to the gradual decrease in the average
age in accessing the Internet, by using deep learning methods. Among the models used for object detection,
the most popular YOLOv4 model was preferred. The data set created by me, which contains 1000 images
labeled as cigarette use, and the open source 1000 labeled pen images provided by OpenImages Google, was
used in order to reduce the number of false positives. It was trained with the YOLOv4 model by giving
separate classes to the cigarette and pen data. 90% F-1 score, 70.54% IoU, 89.63% for cigarette detection,
91.58% average for 91.11% sensitivity was achieved.

![image](https://user-images.githubusercontent.com/103190209/170946035-a1da3d45-57a5-4a0e-8d0d-c24c0a6309ee.png)

Example of real-time cigarette detection and censorship:
![image](https://user-images.githubusercontent.com/103190209/170949017-a9f51e51-c540-4085-9dd1-331bcd407f8e.png)
