# cGAN_YOLOv5
<p align="justify">
This repository is for research usage. Combining cGAN Image dehazing and YOLOv5 object detection, we hope the dehaze process can enhance the 
object detection accuracy on the road. After getting the dehazed results from cGAN, it is then passed to the YOLOv5 model for detection.
</p>

## cGAN Image dehazing
The dehazing part took https://github.com/thatbrguy/Dehaze-GAN as a reference. Number of layers and activation function are modified to enhance dehaze ability.

## YOLOv5 object detection
The training and detection is followed by the instuction of https://github.com/ultralytics/yolov5

# Download our custom dataset and models
| Dataset  | cGAN model | YOLOv5 model | YOLO5 data
| ------------- | ------------- | ------------- | ------------- |
| [Google Drive](https://drive.google.com/drive/folders/1R0kjRxJi3Zr9y-2t5DjPL9IJoxkTE9cK?usp=share_link)  | [Google Drive](https://drive.google.com/drive/folders/1y1_EjFuCmMdXd_SSQpYm1pLLHqxyGKWJ?usp=share_link) | [Google Drive](https://drive.google.com/drive/folders/19MKxnM2qZzQR5ansGLPCRAT6y28s09tX?usp=share_link) | [Google Drive](https://drive.google.com/drive/folders/19s31kXsmUphKi6kF_6iFJOxrcneXwnLI?usp=share_link) |

