# Green Screen Effect using image segmentation:

Tried to implement the green screen using image segmentation by using Mask-RCNN.
Mask-RCNN implementation taken from: https://github.com/matterport/Mask_RCNN

Pretrained Weights can be downloaded from: https://github.com/matterport/Mask_RCNN/releases/download/v2.0/mask_rcnn_coco.h5

## DeepLab Implementation:
Tried 2 different pretrained models for image segmentation using DeepLab.
MobileNetV2 weights: http://download.tensorflow.org/models/deeplabv3_mnv2_pascal_trainval_2018_01_29.tar.gz
Xception weights: http://download.tensorflow.org/models/deeplabv3_pascal_trainval_2018_01_04.tar.gz

Xception offers better result, but is significantly slower than MobileNetV2 (4-5 seconds v/s 1 second)

### Limitations:
Takes about 2-3 second per frame, so it can't work in real time as of now (yes, there are faster implementations that provide better results)