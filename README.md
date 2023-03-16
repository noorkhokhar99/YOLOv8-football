# How to Use YOLOv8 for Real-Time Football Player and Ball Detection: Computer Vision Tutorial



### Steps to run Code

- Clone the repository
```
git clone https://github.com/noorkhokhar99/YOLOv8-football.git
```

- Goto cloned folder
```
cd YOLOv8-football
```

- Install the ultralytics package
```
pip install ultralytics==8.0.0
```

- Do Tracking with mentioned command below
```
#imagefile
python filename.py
```
# video 
```
yolo task=detect mode=predict model=yolov8m-football.pt conf=0.25 imgsz=1280 line_thickness=1 source=test.mp4
```
```
yolo task=detect mode=predict model=yolov8s-football.pt conf=0.25 imgsz=1280 line_thickness=1 source=test.mp4
```
### Results
<table>
  <tr>
    <td>YOLOv8s face detection</td>
  </tr>
  <tr>
    <td><img src="https://github.com/noorkhokhar99/YOLOv8-football/blob/main/How%20to%20Use%20YOLOv8%20for%20Real-Time%20Football%20Player%20and%20Ball%20Detection%20Computer%20Vision%20Tutorial.png"></td>
  </tr>
 </table>



If you find my videos useful,  I would love your support on Pyresearch: https://youtu.be/_eSArKZBWmE


download weight from here: https://drive.google.com/drive/folders/1AqfV35JcWXoxOOpAv8O_9wF57xmXbZVZ?usp=share_link
