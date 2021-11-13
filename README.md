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
   1	Speed limit (20km/h)<br/>
   2	Speed limit (30km/h)<br/>
   3	Speed limit (50km/h)<br/>
   4	Speed limit (60km/h)<br/>
   5	Speed limit (70km/h)<br/>
   6	Speed limit (80km/h)<br/>
   7	End of speed limit (80km/h)<br/>
   8	Speed limit (100km/h)<br/>
   9	Speed limit (120km/h)<br/>
  10	No passing<br/>
  11	No passing for vehicles over 3.5 metric tons<br/>
  12	Right-of-way at the next intersection<br/>
  13	Priority road<br/>
  14	Yield<br/>
  15	Stop<br/>
  16	No vehicles<br/>
  17	Vehicles over 3.5 metric tons prohibited<br/>
  18	No entry<br/>
  19	General caution<br/>
  20	Dangerous curve to the left<br/>
  21	Dangerous curve to the right<br/>
  22	Double curve<br/>
  23	Bumpy road<br/>
  24	Slippery road<br/>
  25	Road narrows on the right<br/>
  26	Road work<br/>
  27	Traffic signals<br/>
  28	Pedestrians<br/>
  29	Children crossing<br/>
  30	Bicycles crossing<br/>
  31	Beware of ice/snow<br/>
  32	Wild animals crossing<br/>
  33	End of all speed and passing limits<br/>
  34	Turn right ahead<br/>
  35	Turn left ahead<br/>
  36	Ahead only<br/>
  37	Go straight or right<br/>
  38	Go straight or left<br/>
  39	Keep right<br/>
  40	Keep left<br/>
  41	Roundabout mandatory<br/>
  42	End of no passing<br/>
  43	End of no passing by vehicles over 3.5 metric tons<br/>

## traffic_recognition.h5
It is CNN model

## yolov4-custom.cfg
It is trained on 4 classes

## s and v
s= server
v= viewer
v.py is testing file where 
s.py is the main server file it is used for sending data to our program from remotly
