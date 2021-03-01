# Deep Regression Segmentation for Cardiac Left-Ventricle MRI

This project was developed during the 2019 [Neural Network Course](http://www.uncini.com/dida/NN/index.html) held by [Prof. Uncini](http://www.uncini.com/) at [Sapienza University of Rome](https://www.uniroma1.it).

It is inspired on [Deep Regression Segmentation for Cardiac Bi-Ventricle MR Images](https://ieeexplore.ieee.org/document/8245780) paper by X. Du et al.  

Since the right ventricles dataset is not open source, we adapted the project only on left ventricles (which is open source and is available in this repository).  


## Getting Started

The project contains only a Jupyter Notebook file. Meet the prerequisite and use it. [Google Colaboratory](https://colab.research.google.com) is recommended.


### Prerequisites

You have two ways of meeting the prerequisites

- First (recommended, online)
  - Use [Google Colaboratory](https://colab.research.google.com) 
  - Done.

- Second (offline)
  - Python3
  - Jupyter ``` pip install jupyterlab ```
  - Tensorflow (via conda, pip, or choose gpu in colab)
    - ``` conda install tensorflow-gpu ```
    - ``` pip install tensorflow-gpu ```
  - OpenCV  ``` pip install opencv-python```
  - Matplotlib ``` pip install matplotlib```
  - Numpy ``` pip install numpy```
  - Scipy ``` pip install scipy```
  - Scikit-image ``` pip install scikit-image```
  - Scikit-learn ``` pip install scikit-learn```
  - Shapely ``` pip install shapely ```
  - OSGEO ``` pip install osgeo ```


## Key Points

In this section, some recap images of the project are presented.

### Preprocessing

![img_preprocessing](https://raw.githubusercontent.com/giabb/quantification-of-cardiac-mri/main/md_img/preprocessing.png)

### Feature extraction

![img_feat_det](https://raw.githubusercontent.com/giabb/quantification-of-cardiac-mri/main/md_img/features_detection.png)

### Coordinates extraction

![img_coord_ext](https://raw.githubusercontent.com/giabb/quantification-of-cardiac-mri/main/md_img/coordinates_extraction.png)

### Overview

![img_overview](https://raw.githubusercontent.com/giabb/quantification-of-cardiac-mri/main/md_img/summary.png)

### Qualitative Analysis

Some qualitative examples are reported. For quantitative examples (Pearson's correlation coefficient, Dice Metric, Hausdorff distance) check the notebook.

![img_qual](https://raw.githubusercontent.com/giabb/quantification-of-cardiac-mri/main/md_img/qualitative_analysis.png)


## Authors

[@giabb](https://github.com/giabb) - [@FabioDiS](https://github.com/FabioDiS)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

