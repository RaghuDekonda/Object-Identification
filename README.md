
# Object Identification Using OpenCV
OpenCV is a free and open-source software library for computer vision and machine learning.
The purpose of OpenCV was to provide a common foundation for computer vision applications and to speed up the usage of machine perception in commercial goods.

Object detection is a computer vision mechanic that involves identifying and localizing objects of interest within an image or a video. It is a challenging task as it involves not only recognizing the presence of an object but also detecting its precise location and size within the image or video.




## Libraries required 
cv2 and matplotlib.pyplot

To install these Libraries open command prompt and run these commands.
```bash
pip install opencv-python
pip install matplotlib

```

## Details of model used

Here in these project we used a pre-trained model "dnn_DetectionModel" 
```bash 
model=cv2.dnn_DetectionModel(frozen_model,config_file)
```
And also we set paramters to the model as follows:
```bash
model.setInputSize(320,320)
model.setInputScale(1.0/127.5)
model.setInputMean((27.5,127,5,127.5))
model.setInputSwapRB(True)
``` 
## Input Image
![boy](https://github.com/RaghuDekonda/Object-Identification/assets/148556000/88b3afb7-e2c0-4bd0-b390-6bfcc2063823)

## Processed Image
![processed image](https://github.com/RaghuDekonda/Object-Identification/assets/148556000/25ccd48b-aae6-43df-89d6-a9a8d0cbdaa9)
## Output Image
![output image](https://github.com/RaghuDekonda/Object-Identification/assets/148556000/5267311c-fc65-497a-8ced-aa6c0317dab5)

