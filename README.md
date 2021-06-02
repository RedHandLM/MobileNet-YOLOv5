# MobileNet-YOLOv5
replace YOLOv5 tag=4.0 backbone : MobileNetV2@1.0 and MobileNetV2@0.25


## DataSet
```
 train:    voc 2007+2012 trainval        21694
 test data: voc-2007-test    4900
 class: 20

```


## Model

| model                          | Epoch | Input   | mAP   | Flops(G) | Params(G) | device | Inference(ms) | Post(ms) |
| --------------------------------- | ----- | ------- | ----- | -------- | --------- | ------ | ------------- | -------- |
| MobileNetV@0.25 + Yolo5s-v4.0     | 300   | 640*640 | 0.551 | 5.6      | 2.79      | 2080TI | 9             | 43       |
|                                   |       |         |       |          |           |        |               |          |


## Reference
 https://github.com/ultralytics/yolov5
