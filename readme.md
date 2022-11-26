# TDT17 - Mini Project
### Road Crack Detection

**1**: <br>
Make sure you have unzipped the data into the a folder with the following structure:
```
|--Norway
    |-- train
    │   |--annotations/xmls
    │   |--images
    |-- test
    │   |--images
```

**2**: <br>
Clone this repo [YOLOv5 Github](https://github.com/ultralytics/yolov5) into the project

**3**: <br>
Install the requirements for the YOLOv5 repo by running the following command in the project folder:
```
pip install -r yolov5/requirements.txt
```
or directly from the YOLOv5 folder:
```
pip install -r requirements.txt
```

**4**: <br>
Follow the instructions in `preprocessing.py` to ready the data for training, and 
`main.ipynb` to train and postprocess.