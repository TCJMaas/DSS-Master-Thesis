# Bridging Dataset Limitations for Underrepresented Crops: Advancing Brassica Yield Prediction with cGAN-Augmented RGB Imagery

## Project Overview
This repository provides the code and data for the Tilburg University Data Science & Society Master's thesis, _Bridging Dataset Limitations for Underrepresented Crops: Advancing Brassica Yield Prediction with cGAN-Augmented RGB Imagery_. The thesis explores the use of Conditional Generative Adversarial Networks (cGANs) to generate synthetic image data for augmenting small datasets of underrepresented crops, and examines their impact on the performance of Convolutional Neural Network (CNN)-based yield prediction models.

## Dataset
**Bender, A., Whelan, B., & Sukkarieh, S. (2019). Ladybird cobbitty 2017 brassica dataset. [https://doi.org/10.25910/5c941d0c8bccb](https://doi.org/10.25910/5c941d0c8bccb)**

For this study, only the manual measurements and in-situ environmental data are stored in this repository as raw data. The autonomously collected RGB images from Week 6 are not stored directly in this repository but are part of the full dataset, which is publicly available under a CC BY-NC-SA 4.0 license. The complete dataset, including the images, can be downloaded [here](http://hdl.handle.net/2123/20187).

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
- Conditional Generative Adversarial Network (cGAN)
- Convolutional Neural Network (CNN)

## For Reproducibility Purposes
To ensure the notebooks run correctly and reproduce the results as intended, follow the steps below.

### Step 1: Download the repository
The notebooks rely on the existing file structure of the repository to import the data. To avoid errors:
- Click the green **"Code"** button at the top of this repository.
- Select **"Download ZIP"** to download the entire repository as a compressed file.
- Extract the ZIP file to maintain the folder structure.
- Inside the extracted repository, locate the `A_raw_data/` folder and extract any additional ZIP files it contains.

### Step 2: Download the image data
Due to GitHub's upload limitations, the file `autonomous_20171115_week_06.7z` must be downloaded separately:
- Download the file from the [original source](http://hdl.handle.net/2123/20187). Using a download manager is recommended.
- This directory has a placeholder folder which should be replaced with the extracted download.

**Note**: This step is optional if you do not intend to reproduce the image preprocessing stage (Phase 2). Subsequent stages can proceed using the already processed data included in the repository.
