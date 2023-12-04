# Object Detection - Person Tracking
This repository is used to fulfill the second task – Person Tracking from Indonesia AI Bootcamp

## Repository Structure
🔗 Result Team:
- [Slide](https://github.com/dikhaarianda/PersonTracking/blob/master/Result-Team/Project%202%20-%20Person%20Tracking.pdf)
- [yolov5s](https://github.com/dikhaarianda/PersonTracking/blob/master/Result-Team/yolov5s.ipynb)
- [yolov5x](https://github.com/dikhaarianda/PersonTracking/blob/master/Result-Team/yolov5x.ipynb)
- [yolov8s](https://github.com/dikhaarianda/PersonTracking/blob/master/Result-Team/yolov8s.ipynb)

🔗 Self Experiment:
- [Object-Detection](https://github.com/dikhaarianda/PersonTracking/blob/master/Self-Experiment/ObjectDetection.ipynb)
- [data.yaml](https://github.com/dikhaarianda/PersonTracking/blob/master/Self-Experiment/data.yaml)

## Report Result-Team
- Preview Dataset

    *Dataset: **Coco-2017 | Class: Person***

    ![Dataset](https://github.com/dikhaarianda/PersonTracking/blob/master/assets/dataset_image.png)

    | Split Dataset | Total Images  |
    |   ---------   |   ---------   |
    |       Train   |       ±3000   |   
    |       Val     |       ±1000   |
    |       Test    |       ±500    |

- Modeling Result
    - YOLOv5s

        ![YOLOv5s](https://github.com/dikhaarianda/PersonTracking/blob/master/assets/yolo5s.jpg)
        ```
        Epoch: 50
        Completed in 39.72 minutes
        ```

    - YOLOv5x

        ![yolo5x](https://github.com/dikhaarianda/PersonTracking/blob/master/assets/yolo5x.jpg)
        ```
        Epoch: 75
        Completed in 156.6 minutes
        ```
    
    - YOLOv8s

        ![yolo5x](https://github.com/dikhaarianda/PersonTracking/blob/master/assets/yolo8s.jpg)
        ```
        Epoch: 75
        Completed in 106.32 minutes
        ```

- Testing with YOLOv8s
    - Image

        ![testImage](https://github.com/dikhaarianda/PersonTracking/blob/master/assets/test_dataset.png)
    
    - Video

         https://github.com/dikhaarianda/PersonTracking/assets/fd97acae-57a1-490c-b51e-21ddb3c744fd

### Conclusion
- For the selection of the model types we have created, namely s and x, the s type has a faster training process compared to the x type, but for the mAP50 result, the x type performs better.

- As for the version selection, v5 has a quicker training process compared to v8, but for the mAP50 result, v8 provides better performance.
