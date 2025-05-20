# Final-Proj-FER-
Repo for the documentation of the development of the FER for our Automated Worker Productivity and Satisfaction Classifier using Computer Vision


<hr>

Training process (from paper):

1st stage: 20 epochs on FER13, no augmentations

2nd stage: 10 epochs on FER13+

3rd stage: 10 epochs on RAF-DB

4th stage: 10 epochs each model on FER13, FER13+ and RAF-DB but now with augmentations + final 10 epochs each model


<hr>

DATASETS USED:

FER13 : https://www.kaggle.com/datasets/msambare/fer2013

FER13+ : https://github.com/Microsoft/FERPlus || https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data

RAF-DB : http://www.whdeng.cn/RAF/model1.html || https://www.kaggle.com/datasets/shuvoalok/raf-db-dataset

<hr>


MODELS USED:

convnext_tiny : https://docs.pytorch.org/vision/main/models/generated/torchvision.models.convnext_tiny.html

coatnet_0 : https://huggingface.co/timm/coatnet_0_rw_224.sw_in1k

swin_tiny : https://huggingface.co/microsoft/swin-tiny-patch4-window7-224

<hr>

REPO for the webapp: https://github.com/zephyrowwa/ESC-w-ConvNeXt

Streamlit webapp: https://escwconvnxt.streamlit.app/
