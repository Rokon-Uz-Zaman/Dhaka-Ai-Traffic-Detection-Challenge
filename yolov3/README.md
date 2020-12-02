## Simple YOLOv3 wrapper for Dhaka-ai challenge 2020


![Image](Image.png)

This repository is based on YOLOv3 implementation from [Ultralytics](https://github.com/ultralytics/yolov3)

Here we simply add all the required configuration files to quickly initiate training and inference. 

Specifically, all the configuration files are targeting dataset for [dhaka-ai](https://dhaka-ai.com/) competition.

More details training and inference is presented in this [colab notebook](https://colab.research.google.com/drive/1x2NZUVJtVqmeSFpBO_XNmv2esMrHPGQ7?usp=sharing)

### Plot Training: 
`from utils import utils; utils.plot_results()` ![image](https://user-images.githubusercontent.com/35966401/96482540-a554f900-125d-11eb-983c-aa77635437eb.png)
### Ground truth
![test_batch0_gt](https://user-images.githubusercontent.com/35966401/96488532-f534bf80-125f-11eb-9adc-a286d4b5f7d5.jpg)
### Prediction
![test_batch0_pred](https://user-images.githubusercontent.com/35966401/96488536-f5cd5600-125f-11eb-8df9-f6c65a370842.jpg)
