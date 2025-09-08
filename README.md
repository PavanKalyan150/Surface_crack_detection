# Surface_crack_detection
This is a Surface Crack Detection project implemented with the Tensorflow. We fine tuning some deep learning models (like VGG 19, VGG16, MobileNetV2, ...). Use Surface Crack Detection dataset available on kaggle.
## Context
Concrete surface cracks are major defect in civil structures. Building Inspection which is done for the evaluation of rigidity and tensile strength of the building. Crack detection plays a major role in the building inspection, finding the cracks and determining the building health.

## Libraries Used
* Tensorflow
* cv2
* Numpy
* scikit Learn

## Dataset
The datasets contains images of various concrete surfaces with and without crack. The image data are divided into two as negative (without crack) and positive (with crack) in separate folder for image classification. Each class has 5000images with a total of 10000 images with 175 x 175 pixels with RGB channels. The dataset is generated from 458 high-resolution images (4032x3024 pixel) with the method proposed by Zhang et al (2016). High resolution images found out to have high variance in terms of surface finish and illumination condition. No data augmentation in terms of random rotation or flipping or tilting is applied.

This dataset is taken from the website Mendeley Data - Crack Detection, contributed by Çağlar Fırat Özgenel.

<p align="center">
<a href="https://github.com/PavanKalyan150/Surface_crack_detection/blob/main/images/data1.png"><img src="https://github.com/PavanKalyan150/Surface_crack_detection/blob/main/images/data1.png" align="center"></a>
</p>