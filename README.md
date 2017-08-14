# CoupleNet
CoupleNet: Coupling Global Structure with Local Parts for Object Detection <br>

The Code is modified from [py-R-FCN] (https://github.com/YuwenXiong/py-R-FCN), Please follow the procudure
in [py-R-FCN] (https://github.com/YuwenXiong/py-R-FCN) to prepare the training data and testing data.<br>

## Main results
 | training data | test data | mAP@0.5 | time/img(ms)
CoupleNet | VOC 07+12 | VOC 07 test | 81.7% | 102
CoupleNet, context | VOC 07+12 | VOC 07 test | 82.1% | 122

 | training data | test data | mAP@[0.5:0.95]| time/img(ms)
CoupleNet | COCO 2014 trainval | COCO test dev | 33.4% | 122

