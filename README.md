# Traffic-sign-using-cnn-yolo

This this Traffic sign classification project using Yolo and cnn

## Yolo Weight File Link
https://drive.google.com/file/d/1MTUr0b0imwYCaycMRmNmn5jYQXzzO7Fq/view?usp=sharing

## Sign name.txt  
1. prohibitory
2. danger
3. mandatory
4. other

## Sign classes.txt 
1	Speed limit (20km/h)
2	Speed limit (30km/h)
3	Speed limit (50km/h)
4	Speed limit (60km/h)
5	Speed limit (70km/h)
6	Speed limit (80km/h)
7	End of speed limit (80km/h)
8	Speed limit (100km/h)
9	Speed limit (120km/h)
10	No passing
11	No passing for vehicles over 3.5 metric tons
12	Right-of-way at the next intersection
13	Priority road
14	Yield
15	Stop
16	No vehicles
17	Vehicles over 3.5 metric tons prohibited
18	No entry
19	General caution
20	Dangerous curve to the left
21	Dangerous curve to the right
22	Double curve
23	Bumpy road
24	Slippery road
25	Road narrows on the right
26	Road work
27	Traffic signals
28	Pedestrians
29	Children crossing
30	Bicycles crossing
31	Beware of ice/snow
32	Wild animals crossing
33	End of all speed and passing limits
34	Turn right ahead
35	Turn left ahead
36	Ahead only
37	Go straight or right
38	Go straight or left
39	Keep right
40	Keep left
41	Roundabout mandatory
42	End of no passing
43	End of no passing by vehicles over 3.5 metric tons

## traffic_recognition.h5
It is CNN model

## yolov4-custom.cfg
It is trained on 4 classes

## s and v
s= server
v= viewer
v.py is testing file where 
s.py is the main server file it is used for sending data to our program from remotly
