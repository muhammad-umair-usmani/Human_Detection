# Human Detection
Human Detection using yolov5m


In this repository I have trained yolov5m on WiderPerson Dataset.




# Introduction

The WiderPerson dataset is a pedestrian detection benchmark dataset in the wild, of which images are selected from a wide range of scenarios, no longer limited to the traffic scenario. We choose 13,382 images and label about 400K annotations with various kinds of occlusions. We randomly select 8000/1000/4382 images as training, validation and testing subsets. Similar to CityPersons and WIDER FACE datasets, we do not release the bounding box ground truths for the test images. Users are required to submit final prediction files, which we shall proceed to evaluate.


![image](./dataset.png)

# Training and Data Preparation

The included code, which is in form of Ipython Notebook, downloads the dataset and perform processing.

Finally yolov5m is trained. Below are training metrics and performanceimages

![image](./training_metrics.png)
![image](./training_logs.png)
![image](./training_loss.png)
![image](./training_lr.png)

![image](./labels.jpg)
![image](./labels_correlogram.jpg)

![image](./train_batch2.jpg)



