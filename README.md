

# Arterial Atlas:

## Introduction

We present an atlas of brain arterial territories based on the distribution of acute and subacute ischemic strokes in the diffusion weighted MRIs of 1,298 patients. The atlas  covers supra- and infra-tentorial regions and contains hierarchical segmentation levels created by a fusion of vascular and classical anatomical criteria. This deformable 3D digital atlas allows automatic and reproducible exploration of large-scaled data.


<p align="middle">
    <img src="assets/atlas_pic.png", width="600" height="400">
</p>


### Root
The `${ROOT}` is described as below.
```
${ROOT}
|-- data
```

* `data` contains two atlases in nii and nii.gz format and the corresponding label table in txt.

## Reference  

## Note
Our Atlas is based on JHU_MNI_SS (181x217x181). For compatibility with the MNI152 template from FSL (182x218x182), one can either “zero pad” the Atlas to the last dimension or “crop” the last dimension of MNI152-FSL. The JHU_MNI_SS (original and “MNI152-FSL compatible”) is downloadable from https://github.com/muschellij2/Eve_Atlas

## License 
Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
