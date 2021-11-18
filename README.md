# Object Detection using EfficientDet

This repository contains training of [EfficientDet](https://github.com/roboflow-ai/Monk_Object_Detection/tree/master/4_efficientdet/lib) on [Aquarium](https://public.roboflow.com/object-detection/aquarium) Dataset and using the trained model to detect objects on images and videos.

The below images shows an example of object detection in image and video.

![Alt text](https://github.com/kalpiree/Neural_networks/blob/main/image_inference/original_imgs/actual_2.jpg?raw=true "Actual Image")
![Alt text](https://github.com/kalpiree/Neural_networks/blob/main/image_inference/infer_imgs/infer_2.jpg?raw=true "Object-detected Image")

The repository contains following files:
```
├── main.ipynb                   # Jupyter notebook to train and infer code.
├── trained_model                # Directory containing trained model
├── image_inference              # Directory containing original and object-detected images
   ├── original_imgs              # Directory containing original images
   ├── infer_imgs                 # Directory containing inferred images
├── video_inference              # Directory containing original and object-detected images
   ├── original_vids              # Directory containing original videos
   ├── infer_vids                 # Directory containing inferred videos
└── README.md
```


## How to use?

### 1. Train model

a. Run **EfficientDet Code** section in the Jupyter notebook to download the model architecture.

b. Run **Preprocessing Dataset** section in the Jupyter notebook to download and preprocess the dataset.

c. Run **Training** section in the Jupyter notebook to train the model.

### 2. Image Inference

The images can also be inferred using a pre-trained model hosted on Google Drive.

a. Run **Image Inference** section in the Jupyter notebook to detect object in images.


### 3. Video Inference

The videos can also be inferred using a pre-trained model hosted on Google Drive. The inferred videos are automatically downloaded by the notebook which can be viewed in a local media player.

a. Run **Video Inference** section in the Jupyter notebook to detect object in videos.


## References

[Tan, Mingxing, Ruoming Pang, and Quoc V. Le. "Efficientdet: Scalable and efficient object detection." Proceedings of the IEEE/CVF conference on computer vision and pattern recognition. 2020.](https://openaccess.thecvf.com/content_CVPR_2020/papers/Tan_EfficientDet_Scalable_and_Efficient_Object_Detection_CVPR_2020_paper.pdf)
