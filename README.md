# Parser-Free Virtual Try-on

Image virtual try-on aims to fit a garment image (target clothes / item) to a person image (model image). Prior methods are heavily
based on human parsing. However, slightly-wrong segmentation results would lead to unrealistic try-on images with
large artifacts.
This work does not use human parsing.

## Environment
anaconda3

pytorch 1.1.0

torchvision 0.3.0

cuda 9.0

cupy 6.0.0

opencv-python 4.5.1

8 GTX1080 GPU for training; 1 GTX1080 GPU for test

python 3.6

## Installation
conda create -n tryon python=3.6

source activate tryon     or     conda activate tryon

conda install pytorch=1.1.0 torchvision=0.3.0 cudatoolkit=9.0 -c pytorch

conda install cupy     or     pip install cupy==6.0.0

pip install opencv-python
