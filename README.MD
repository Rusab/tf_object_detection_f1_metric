## F1 Metric for single class object detection with Tensorflow Object Detection API Models
### Usage:
Add path to Ground truth and Prediction Tensorflow CSV format files:

    ground_truth = pd.read_csv('test_annotations.csv')
    pred = pd.read_csv('predict_test_frcnn.csv')


Set IoU Threshold:

    iou_thres = 0.5
---
*IoU calculation code is taken from Treefive's repo -* https://github.com/Treesfive/calculate-iou