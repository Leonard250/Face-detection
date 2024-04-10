Project Summary:

The project focuses on implementing and optimizing the YOLOv3 object detection algorithm for real-time applications. It comprises multiple tasks, including running the provided notebook on Kaggle, understanding its components, explaining key sections, adding an extra class for face detection, and implementing face detection using a webcam.

1. **YOLOv3 Overview:**
   - YOLOv3 is a renowned object detection algorithm known for its speed and accuracy.
   - It utilizes a single-stage detection approach with a Darknet-53 backbone, anchor boxes, and multi-scale bounding box prediction.
   - Balances speed and accuracy, making it suitable for real-time applications.

2. **Tasks Completed:**
   - **Task 1:** Ran the provided notebook on Kaggle, trained the model for 30 epochs, and plotted the loss diagram.
   - **Task 2:** Explained critical sections from the notebook, such as the iou function, nms function, YOLOv3 class, Scale Prediction class, and the role of anchors in object detection using YOLO.
   - **Task 3:** Added an extra class "face" to the dataset, annotated the data in YOLO format, merged it with pre-existing data, and trained the model. Observed that adding the face class improved model accuracy.
   - **Face Detection in Action:** Implemented face detection using a webcam, as Kaggle notebook couldn't access the local webcam. Utilized the downloaded checkpoint from Kaggle and adapted the code accordingly.
   - **Improving Performance:** Suggested strategies to enhance model performance, including removing the "person" class and increasing the number of images for the "face" class. Tried to augment data using additional datasets but encountered format compatibility issues.

3. **YOLO Data Format:**
   - Detailed the YOLO data format for annotating objects in images or videos, explaining its structure, normalization, and benefits like standardization, ease of use, and compatibility with deep learning frameworks.

4. **Conclusion:**
   - The project demonstrates a comprehensive understanding of YOLOv3 and its practical implementation for object detection tasks.
   - Highlights the significance of key components such as anchor boxes, loss functions, and post-processing techniques like non-maximum suppression.
   - Suggests potential improvements to enhance model accuracy and performance, emphasizing data augmentation and class-specific optimizations.
  
     ![image](https://github.com/Leonard250/YOLO-Face-detection/assets/141337656/5d351973-544a-426f-8ffe-801abf23a883)
