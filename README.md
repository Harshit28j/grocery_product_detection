## Grocery Object Detection

Clone the repository.

### Install the necesaary modules first
```
python -m pip install -r requirements.txt
```

### To run script write in CLI:
```
python detect.py --weights best.pt --source 0
```
where '--source 0': Indicates that the source is the camera

you can replace source and write the path of video or image
### Object detection with image
```
python detect.py --weights best.pt --source path/to/your/image.jpg
```

### Object detection with video
```
python detect.py --weights best.pt --source path/to/your/video.mp4
```
