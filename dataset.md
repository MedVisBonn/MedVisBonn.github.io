---
layout: page
title: Download
permalink: /download/
---
### Zenodo Link
You can find the download link for our SICS-155 dataset here: [Dataset](https://doi.org/10.5281/zenodo.15044589).\
**Take Note**⚠️: Don't forget to [register](registration.md) before downloading the dataset.

**i3d features**: We can also provide you with preprocessed inflated 3D (i3d) features for the videos, please contact us if you are interested ([Mail](mailto:ag.wintergerst@gmail.com))!

### Details 
Currently only the **training** and **validation** subsets are published. After the challenge is finished, we will also release the remaining videos in the **test** set. The 3 sets were stratified by video duration so that an similiar number of short, medium and long videos are contained in each. 

The provided **ground truth** files are text (txt) files where each line corresponds to a video frame and contains the class label. You can find numeric indecies for each class-label in the mapping.txt file that is also provided. The additional CSV files contain the raw annotations in table format, but we advice to use the test files in the groundTruth/ folder due to the preprocessing we perfomed.

Should you have questions regarding the dataset, feel free to reach out ([Mail](mailto:ag.wintergerst@gmail.com))!

### Evaluation
We are providing an evaluation script that calculates our required metrics on a folder of ground truth files and a folder of prediciton files. 
**Evaluation Script**⚙️: [Github](https://github.com/MedVisBonn/SICS155_challenge)

The **ground truth** and **prediction** files should be text (txt) files where each line corresponds to a video frame and contains the phase label (e.g. background). You can find numeric indecies for each class-label in the mapping.txt file that is also provided. 

