# Object Detection Loss comparison

Some work to compare various object detection loss functions

## Confusion Matrix

GIou             |  DIoU |                                  CIoU
:-------------------------:|:-------------------------:|:-------------------------:
![](yv5-n-giou/confusion_matrix.png)  |  ![](yv5-n-diou/confusion_matrix.png) | ![](yv5-n-ciou/confusion_matrix.png)

## mAP50-95 (on VOC test dataset)

GIou             |  DIoU |                                  CIoU
:-------------------------:|:-------------------------:|:-------------------------:
0.458  |  0.461 | 0.465


## Validation Summary (using best.pt)

GIou             |  DIoU |                                  CIoU
:-------------------------:|:-------------------------:|:-------------------------:
![](yv5-n-giou/val_summary.png)  |  ![](yv5-n-diou/val_summary.png) | ![](yv5-n-ciou/val_summary.png)

## Training time (in hours)

GPU - 1080Ti

GIou             |  DIoU |                                  CIoU
:-------------------------:|:-------------------------:|:-------------------------:
13.802   |  13.639 | 14.384 
