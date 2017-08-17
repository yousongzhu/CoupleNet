# CoupleNet
CoupleNet: Coupling Global Structure with Local Parts for Object Detection

The Code is modified from [py-R-FCN](https://github.com/YuwenXiong/py-R-FCN), please follow the procedure in it to prepare the training data and testing data.
Using the default hyperparameters and iterations, you can achieve a mAP around 81.7%.<br>

## Main results
　| training data | test data | mAP@0.5 | time/img(ms)
------ | ----- | ------ | ------ | ------
CoupleNet, ResNet-101<sup>**</sup> | VOC 07+12 | VOC 07 test | 81.7% | 102
CoupleNet, ResNet-101 | VOC 07+12 | VOC 07 test | 82.1% | 122
CoupleNet, ResNet-101 | VOC 07++12 | VOC 12 test | 80.4% | 122

**: without adding context.

　| training data | test data | mAP@[0.5:0.95]| time/img(ms)
 ------ | ----- | ------ | ------ | ------
CoupleNet, ResNet-101 | COCO 2014 trainval | COCO test dev | 34.4% | 122

[VOC 0712 model (trained on VOC 07+12, mAP 81.7%)](https://pan.baidu.com/s/1eSF1EYu)

### Citing CoupleNet

If you find CoupleNet useful in your research, please consider citing:
