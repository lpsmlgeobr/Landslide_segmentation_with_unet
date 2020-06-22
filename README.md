 Repository with the code used in the paper Landslide Segmentation with Unet: Evaluating Different Sampling Methods and Patch Sizes

---

### Data

The data used in this research and the best models' weights are available and can be requested by sending an email to lpsoares@usp.br


### Dependencies

The dependecies.txt file contains all the libraries used in the preprocessing step. To install, follow the steps below:

1. cd to the directory where requirements.txt is located.
2. activate your virtualenv.
3. run: pip install -r requirements.txt in your shell.

The notebooks used to train and evaluate the networks should be uploaded to Google Drive and opened in the Google Colaboraty Virtual Environment. 

---

## Overview

### Preprocessing

1. [Band Stacking](https://github.com/lpsmlgeobr/Landslide_segmentation_with_unet/blob/master/notebooks/0_%20BandStacking.ipynb)

2. [Binary Maks](https://github.com/lpsmlgeobr/Landslide_segmentation_with_unet/blob/master/notebooks/1_generate_binary_mask.ipynb)

3. [Image Sampling](https://github.com/lpsmlgeobr/Landslide_segmentation_with_unet/blob/master/notebooks/2_Sampling_images.ipynb)

4. [Load image as Arrays](https://github.com/lpsmlgeobr/Landslide_segmentation_with_unet/blob/master/notebooks/4_load_images_as_arrays.ipynb)

5. [Data Augmentation](https://github.com/lpsmlgeobr/Landslide_segmentation_with_unet/blob/master/notebooks/5_data_augmentation.ipynb)

## Training

#### RapidEye

1. [Regular Sampling](https://github.com/lpsmlgeobr/Landslide_segmentation_with_unet/blob/master/notebooks/Training_regular_RapidEye.ipynb)

2. [Random Sampling](https://github.com/lpsmlgeobr/Landslide_segmentation_with_unet/blob/master/notebooks/Training_random_RapidEye.ipynb)


#### RapidEye + Augmentation

1. [Regular Sampling](https://github.com/lpsmlgeobr/Landslide_segmentation_with_unet/blob/master/notebooks/Training_regular_RapidEye%2BAugmentation.ipynb)

2. [Random Sampling](https://github.com/lpsmlgeobr/Landslide_segmentation_with_unet/blob/master/notebooks/Training_random_RapidEye%2BAugmentation.ipynb)


#### RapidEye + DEM

1. [Regular Sampling](https://github.com/lpsmlgeobr/Landslide_segmentation_with_unet/blob/master/notebooks/Training_regular_RapidEye%2BDEM.ipynb)

2. [Random Sampling](https://github.com/lpsmlgeobr/Landslide_segmentation_with_unet/blob/master/notebooks/Training_random_RapidEye%2BDEM.ipynb)

#### RapidEye + DEM + Augmentation

1. [Regular Sampling](https://github.com/lpsmlgeobr/Landslide_segmentation_with_unet/blob/master/notebooks/Training_regular_RapidEye%2BDEM%2BAugmentation.ipynb)

2. [Random Sampling](https://github.com/lpsmlgeobr/Landslide_segmentation_with_unet/blob/master/notebooks/Training_random_RapidEye%2BDEM%2BAugmentation.ipynb)

---

## Results

1. [Georeferencing the Results](https://github.com/lpsmlgeobr/Landslide_segmentation_with_unet/blob/master/notebooks/Georeferencing_the_results.ipynb)
 




