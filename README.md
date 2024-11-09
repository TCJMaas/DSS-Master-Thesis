# Bridging Dataset Limitations for Underrepresented Crops: Advancing Brassica Yield Prediction With cGAN-Augmented RGB Imagery

## Project Overview
This repository provides the code and data for the Tilburg University Data Science & Society Master's thesis, _Bridging Dataset Limitations for Underrepresented Crops: Advancing Brassica Yield Prediction with cGAN-Augmented RGB Imagery_. The thesis explores the use of Conditional Generative Adversarial Networks (cGANs) to generate synthetic image data for augmenting small datasets of underrepresented crops, and examines their impact on the performance of Convolutional Neural Network (CNN)-based yield prediction models.

## Dataset
**Bender, A., Whelan, B., & Sukkarieh, S. (2019). Ladybird cobbitty 2017 brassica dataset. [https://doi.org/10.25910/5c941d0c8bccb](https://doi.org/10.25910/5c941d0c8bccb)**

For this study, only the manual measurements, environmental data, and RGB images from week 6 were used and are stored in this repository as raw data. The full dataset is publicly available under a CC BY-NC-SA 4.0 license and can be downloaded [here](http://hdl.handle.net/2123/20187).

## Directory Structure
- **[`data/`](data/)**: Contains subdirectories with the raw and processed datasets:
  - **[`A_raw_data/`](data/A_raw_data/)**: Raw data as downloaded from the original dataset
  - **[`B_processed_data/`](data/B_processed_data/)**: Processed versions used for model training and evaluation
- **[`notebooks/`](notebooks/)**: Jupyter notebooks organized by project phase:
  - **Phase 1**: `01_preprocessing_tabular_data.ipynb`
  - **Phase 2**: `02_preprocessing_image_data.ipynb`
  - **Phase 3**: `03_exploratory_data_analysis.ipynb`
  - **Phase 4**: `04_synthetic_data_generation.ipynb`
  - **Phase 5**: `05_yield_prediction.ipynb`

## Languages
- Python

## Algorithms
- [Conditional Generative Adversarial Network (cGAN)](https://doi.org/10.48550/arXiv.1411.1784)
- [Convolutional Neural Network (CNN)]()

## Libraries and Tools
| **Category**          | **Library/Tool and Version**                                                    |
|:----------------------|:--------------------------------------------------------------------------------|
| Data preprocessing    | [ list specific versions ]<br>[ list specific versions ] |
| Model development     | [ list specific versions ]<br>[ list specific versions ] |
| Model evaluation      | [ list specific versions ]<br>[ list specific versions ] |
| Visualization         | [ list specific versions ]<br>[ list specific versions ] |
