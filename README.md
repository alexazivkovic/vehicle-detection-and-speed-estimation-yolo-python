# vehicle-detection-and-speed-estimation-yolo-python

This project uses YOLOv3 for Vehicle detection and speed estimation

This project imlements the following tasks in the project:

1. Vehicle counting
2. Speed estimation
3. Dumps all these details into a CSV file

# To run the project:

1. Download the code or simply run:

```
$ git clone https://github.com/alexazivkovic/vehicle-detection-and-speed-estimation-yolo-python
```

2. To install required dependencies, run:

```
$ cd vehicle-detection-and-speed-estimation-yolo-python
$ pip3 install -r requirements.txt
```

3. Download yolo weights file by:

```
$ bash download_weights
```

4. Make sure you change the line of detection and lane segmentation according to your video and fine tune the threshold and confidence for YOLO model

5. Run

```
$ Python3 main.py -input /path/to/video/file.avi -output /path/for/output/video/file.avi -yolo /path/to/YOLO/directory/
```
