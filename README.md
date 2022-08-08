# YoloV4-tiny ONNX
yolov4-tiny.onnx

Download already converted (onnx) model: [Download](https://github.com/TheYoungBeast/YoloV4-Tiny-ONNX/raw/main/yolov4-tiny.onnx)

## Yolov4-tiny

- cfg source: [yolov4-tiny.cfg](https://raw.githubusercontent.com/AlexeyAB/darknet/master/cfg/yolov4-tiny.cfg)
- weights source: [yolov4-tiny.weights](https://github.com/AlexeyAB/darknet/releases/download/darknet_yolo_v4_pre/yolov4-tiny.weights)

## Script

Script source: [export_onnx.py](https://github.com/linghu8812/tensorrt_inference/blob/master/project/Yolov4/export_onnx.py)

## Command

```shell
python3 export_onnx.py --cfg_file yolov4/yolov4-tiny.cfg --weights_file yolov4/yolov4-tiny.weights --output_file yolov4-tiny.onnx
```
