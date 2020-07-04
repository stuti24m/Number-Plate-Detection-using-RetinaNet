# Number-Plate-Detection-using-RetinaNet
😄 This is a part of Object Detection on Custom Dataset with **TensorFlow 2** and **Keras** using Python.

Usually, the result of object detection contains three elements:

    1. list of bounding boxes with coordinates
  
    2. the category/label for each bounding box
  
    3. the confidence score (0 to 1) for each bounding box and label

*RetinaNet is built on top of two crucial concepts - Focal Loss and Featurized Image Pyramid:

    -Focal Loss is designed to mitigate the issue of extreme imbalance between background and foreground with objects of interest. It assigns more weight on hard, easily misclassified examples and small weight to easier ones.

    -The Featurized Image Pyramid is the vision component of RetinaNet. It allows for object detection at different scales by stacking multiple convolutional layers.
