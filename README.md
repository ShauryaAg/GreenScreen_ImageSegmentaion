# Green Screen Effect using image segmentation:

Tried to implement the green screen using image segmentation by using Mask-RCNN.
Mask-RCNN implementation taken from: https://github.com/matterport/Mask_RCNN

Pretrained Weights can be downloaded from: https://github.com/matterport/Mask_RCNN/releases/download/v2.0/mask_rcnn_coco.h5

### Limitations:
Takes about 2-3 second per frame, so it can't work in real time as of now (yes, there are faster implementations that provide better results)