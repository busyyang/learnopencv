# Object detection using YOLOv5 model

This project provides the inference code for YOLOv5. You can use it in Python and C++.

Please Download the ONNX weight from [BaiduNet](https://pan.baidu.com/s/19ZQxfFrFhukUC6xKSsvuoA) (code: yolo) firstly.

If you run it in C++, please ensure you have install a OpenCV 4.0 or higher (tested in 4.5.0).

Once you have trained your own weights from [ultralytics/yolov5](https://github.com/ultralytics/yolov5). Please run the `convert_onnx.py` to convert *.pt model to *.ONNX.

~~~bash
python convert_onnx.py --net_type yolov5s --num_classes 80
~~~
In case of error happen, ensure your pytorch is >= 1.7.0.

and we thank [hpc203](https://github.com/hpc203/yolov5-dnn-cpp-python) for his work.

If you could read Chinese, this [blog](https://blog.csdn.net/nihate/article/details/112731327) maybe help you.

