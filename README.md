# Corneal endothelial cell quantification in transmission in vivo imaging (Supporting code)

<p align="center">
  <img src="ECD processing.png" alt="Overview of corneal endothelial cell quantification workflow" width="700">
</p>

This repository contains the supporting code for the preprint:
**"Corneal endothelial cell quantification in transmission in vivo imaging"**.

Preprint for this work is available in this repository: 'Preprint.pdf'

Main notebook for training and inference: `U-net ECD.ipynb`

Weights for U-net denoising (Google Drive): [Denoising](https://drive.google.com/file/d/1zw5k49EKRgnYeDd7PKXh9kMwnlGTavT_/view?usp=sharing)

Weights for U-net cell segmentation (Google Drive): [Segmentation](https://drive.google.com/file/d/1HvsMbiHQqGQxt5qFdrribDfG-bdQkFmJ/view?usp=sharing)

## Installation and Running

1. Create conda environment from the provided environment files: CondaEnvironment_Unet.yml'.
  conda env create -f CondaEnvironment_Unet.yml

2. Activate environment and launch jupyter notebook
  conda activate CondaEnvironment_Unet  
  jupyter notebook
  
3. Load notebok 'U-net ECD.ipynb'
  
4. Specify two folders (IN folder and OUT folder) for input -> output conversion. Images should be .jpg or .png and have matching names in IN and OUT folder.

5. Proceed with the training and inference


