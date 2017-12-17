# HDRstyle-Brightness-Enhance

Tensorflow implementation for learning an image-to-image color enhancement using GAN structure (semi-supervised).

For image example:
![example](docs/images/example.jpg)

Network structure looks:
![network_structure](docs/images/network.jpg)

This repository contains train and test codes for reproduce.
However, a description for training will be updated later.

--------------------------

## Prerequisites
- tensorflow r1.2 or higher
- numpy 1.13.1
- scipy 0.19.1
- pillow 4.2.1

## Getting Started
### Installation
- Install tensorflow from https://github.com/tensorflow/tensorflow
- Clone this repo:
```bash
git clone https://github.com/gudtjr8462/HDRstyle-brightness-enhance
cd HDRstyle-brightness-enhance
```

## Test Details
```bash
CUDA_VISIBLE_DEVICES=0 python main.py --input=/path/to/data/input_name  --mode=test
```

## License ##
This software is being made available under the terms in the [LICENSE](LICENSE) file.

Any exemptions to these terms requires a license from the Pohang University of Science and Technology.

## About Coupe Project ##
Project ‘COUPE’ aims to develop software that evaluates and improves the quality of images and videos based on big visual data. To achieve the goal, we extract sharpness, color, composition features from images and develop technologies for restoring and improving by using it. In addition, personalization technology through user preference analysis is under study.
  
Please checkout out other Coupe repositories in our [Posgraph](https://github.com/posgraph) github organization.

## Useful Links ##

  * [Coupe Library](http://coupe.postech.ac.kr/)
  * [POSTECH CG Lab.](http://cg.postech.ac.kr/)
