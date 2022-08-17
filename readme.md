# YOLOv3 based Mask and non-mask identifier

## About

It is simple implementation of YOLOv3 model for detecting masked perople apart from unmasked ones in real time. Thid sydtem can be useful for entrance in this pandemic.

## Useful Links

Do follow following links for dataset, model, and trained weight file.

[Dataset From Kaggle](https://www.kaggle.com/datasets/crained/wearingmaskc19)

[Trained Weight file](https://drive.google.com/file/d/1-H_DIlCpxvlFSbZKabNWZlG1ebniHzFH/view?usp=sharing)

[YOLO darknet from AlexeyAB](https://github.com/AlexeyAB/darknet)

## Step1: Requirements
pip install -r requirements.txt

- [Download Weights](https://drive.google.com/file/d/1-H_DIlCpxvlFSbZKabNWZlG1ebniHzFH/view?usp=sharing) file. ( If you do not want to train on your own )

## Inference
python test_on_photo.py 

python test_on_video.py

## Results

### Outputs

#### Images

![Tested on image](https://github.com/AnjaanKhadka/Face-mask-Detection-using-YOLOv3/blob/master/images/result.jpg)

#### Video

![Tested on video](https://github.com/AnjaanKhadka/Face-mask-Detection-using-YOLOv3/blob/master/images/result_video.gif)
