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

The uploaded models are organised as below:

```
root
  ├──VaTr_pop909_epoch_10.pth         Variation Transformer model trained on the POP909-TVar dataset for 10 epochs
  │    
  ├──VaTr_vgmidi_epoch_10.pth         Variation Transformer model trained on the VGMIDI-TVar dataset for 10 epochs
  │    
  ├──MuTr_pop909_epoch_10.pth         Music Transformer model trained on the POP909-TVar dataset for 10 epochs
  │       
  ├──MuTr_vgmidi_epoch_10.pth         Music Transformer model trained on the VGMIDI-TVar dataset for 10 epochs
  │    
  ├──FaTr_pop909_epoch_10.pth         fast-Transformer model trained on the POP909-TVar dataset for 10 epochs
  │    
  ├──FaTr_vgmidi_epoch_10.pth         fast-Transformer model trained on the VGMIDI-TVar dataset for 10 epochs
  │   
  ├──MAMA_pop909.zip                  state transition matrix extracted from the POP909-TVar dataset for Variation Markov 
  │ 
  └──MAMA_vgmidi.zip                  state transition matrix extracted from the VGMIDI-TVar dataset for Variation Markov
```
