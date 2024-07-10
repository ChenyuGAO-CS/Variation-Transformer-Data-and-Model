# Variation-Transformer-Data-and-Model
This repository contains the datasets and models to reproduce the results of the paper: Gao et al., Variation Transformer: New datasets, models, and comparative evaluation for symbolic music variation generation, in ISMIR 2024.

## POP909-TVar and VGMIDI-TVar datasets
The POP909-TVar and VGMIDI-TVar datasets can be accessed in the ```'dataset'``` folder as .zip files.

Themes' names are ended with the suffix ```'_0'```. Variations for a theme share the same prefix of the theme's name, but end up with the suffix ```'\_[an integer > 0]'```.   _For example, '052_B_1.mid' is an annotated variation for the theme ('052_B_0.mid')._

```
dataset
  ├──POP909-TVar/         themes-and-variation pairs extracted from the POP909 dataset
  │      │
  │      ├──train/        
  │      │
  │      └──test/         
  │ 
  └──VGMIDI-TVar/         themes-and-variation pairs extracted from the VGMIDI dataset
         │
         ├──train/        
         │
         └──test/         
```

## Models
Please go to this link to download the corresponding models: https://zenodo.org/records/12704642
