# Digital recognition

## Documentation description

- match_similarity

> 方法：模版匹配加形态学相似度计算
>
> temple：用于模版匹配的图片

- yolov5_numberDetect

> 方法：yolov5训练模型
>
> number_data:用来训练的数字
>
> **number_detect_IR**:由pt模型转成的IR模型
>
> 🚀特殊说明：IR模型可以用在树莓派上，NCS2加速推理，加速后能到3fps。
>
> weights:权重文件
>
> 🚀特殊说明：best.pt为最好情况下的权重文件，last.pt是做后一次运算的权重文件。
>
> **其余png图片为训练的结果展示**

## Confusion matrix

![confusion_matrix](./yolov5_numberDetect/confusion_matrix.png)

