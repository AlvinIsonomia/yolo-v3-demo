# yolo-v3-demo

**西安电子科技大学2019电院课程设计作业**

15020199045 刘畅

# 准备

整个模型运行在 pytorch 上，并需要OpenCV v2进行必要的图片操作。

imgs为测试集，运行结果良好。

data为coco数据集标注结果。

det中为运行图片标注的框图结果。

cfg中为标注的可选项，包括选框的颜色，字体大小等


# 运行方法(demo)

python dectect.py --images dog-cycle-car.png --det det

若正确运行，得到的输出为：

Loading network.....

Network successfully loaded

dog-cycle-car.png    predicted in  2.456 seconds

Objects Detected:    bicycle truck dog

/----------------------------------------------------------

SUMMARY

/----------------------------------------------------------

Task                     : Time Taken (in seconds)

Reading addresses        : 0.002

Loading batch            : 0.120

Detection (1 images)     : 2.457

Output Processing        : 0.002

Drawing Boxes            : 0.076

Average time_per_img     : 2.657

/----------------------------------------------------------
