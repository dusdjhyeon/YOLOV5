# yolov5
Mobile Programming Assignments (yolov5 and test api)

This repository is a slightly modified code from the original repository that allows Django to receive photos detected through yolo.
Source: https://github.com/ultralytics/yolov5.<br>
If you want a modified code, please clone this repository.<br>
The changedetection.py file requires the appropriate settings for your Django site.

``` bash
$ cd yolov5
$ python -m venv ./venv
$ source ./venv/bin/activate
$ pip install -r requirements.txt
$ python detect.py --source 0
```
