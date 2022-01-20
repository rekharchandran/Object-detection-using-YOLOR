# Traffic sign detection using YOLOR

#### YOLOR Object Detection

YOLOR is a state-of-the-art machine learning algorithm for object detection, different from YOLOv1-YOLOv5 due to the difference in authorship, architecture, and model infrastructure. YOLOR stands for “You Only Learn One Representation”, not to be confused with YOLO versions 1 through 4, where YOLO stands for “You Only Look Once”


YOLOR is specifically for object detection, rather than other machine learning use cases such as object identification or analysis. This is because object detection is focused around the general identifiers which make the object fall under a certain category or class. In contrast, other types of machine learning use cases require more exact processes. Object identification requires the machine learning model to be attuned to the range of nuances that would constitute objects from each other.

For example, object analysis is often used for medical purposes, where classic object detection algorithms made for differentiating cars, and people would be ineffective.

YOLOR for Object Detection https://github.com/WongKinYiu/yolor

#### YOLOR performance and precision

The new YOLOR algorithm aims to accomplish tasks using a fraction of predicted additional costs for comparative algorithms. Hence, YOLOR is a unified network that can process implicit and explicit knowledge together and produce a general representation that is refined because of that methodology.

In combination with state-of-the-art methods, the YOLOR achieved comparable object detection accuracy as the Scaled YOLOv4, while the inference speed was increased by 88%. This makes YOLOR one of the fastest object detection algorithms in modern computer vision. On the MS COCO dataset, the mean average precision of YOLOR is 3.8% higher compared to the PP-YOLOv2, at the same inference speed.

![image](https://user-images.githubusercontent.com/50706192/150343624-d8839de3-5404-4dd3-b9cb-b96bd1a2ba85.png)

The YOLO-R research paper:https://arxiv.org/pdf/2105.04206v1.pdf
