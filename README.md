# RS_evaluation

This repository contains code used in RS22 evaluation task.\
To reproduce the experiments, one need to change directories' names for datasets' downloadings and models'saving specified in the beginning of the notebooks. Also, attaching google drive have to be not done if one do not want to use GD.\
If running in colab and saving models on GD, it's totally ok to change nothing.\
You have to have kaggle API token in running directory to be allowed to download the data.\
If one wants to get the fine-tuned models parameters, here they are: [link](https://drive.google.com/drive/folders/1aD3cEXsV6yJPPyNXoBHMjUBzEKCTJtXw?usp=sharing) \
Mosels used: [REGNET_Y_32GF](https://pytorch.org/vision/0.14/models/generated/torchvision.models.regnet_y_32gf.html#regnet-y-32gf), [EFFICIENTNET_V2_L](https://pytorch.org/vision/0.14/models/generated/torchvision.models.efficientnet_v2_l.html#efficientnet-v2-l), [VIT_B_16](https://pytorch.org/vision/0.14/models/generated/torchvision.models.vit_b_16.html#vit-b-16), [CONVNEXT_BASE](https://pytorch.org/vision/0.14/models/generated/torchvision.models.convnext_base.html#convnext-base)\
Datasets used: [Animals](https://www.kaggle.com/datasets/iamsouravbanerjee/animal-image-dataset-90-different-animals), [Weather](https://www.kaggle.com/datasets/jehanbhathena/weather-dataset)
