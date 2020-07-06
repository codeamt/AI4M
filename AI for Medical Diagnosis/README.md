## AI for Medical Diagnosis 

**AI4M Course 1(C1):** Using a convolutional neural network (CNN) to perform image classification and segmentation for diagnoses of lung and brain disorders. 

## Contents 

```
.
├── README.md
├── tree.txt
├── week_1
│   ├── assignment
│   │   └── Chest\ X-Ray\ Medical\ Diagnosis\ with\ Deep\ Learning.ipynb
│   └── lectures
│       ├── AI4M_C1_W1_lecture.ipynb
│       ├── AI4M_C1_W1_lecture_ex_01.ipynb
│       ├── AI4M_C1_W1_lecture_ex_02.ipynb
│       ├── AI4M_C1_W1_lecture_ex_03.ipynb
│       └── AI4M_C1_W1_lecture_ex_04.ipynb
├── week_2
│   ├── assignment
│   │   ├── Evaluation\ of\ Diagnostic\ Models.ipynb
│   │   ├── train_preds.csv
│   │   ├── util.py
│   │   └── valid_preds.csv
│   └── lectures
└── week_3
    ├── assignment
    │   ├── BraTS-Data
    │   │   ├── imagesTr
    │   │   │   ├── BRATS_001.nii.gz 
    │   │   │   ├── BRATS_002.nii.gz 
    │   │   │   └── BRATS_003.nii.gz 
    │   │   ├── labelsTr
    │   │   │   ├── BRATS_001.nii.gz
    │   │   │   ├── BRATS_002.nii.gz
    │   │   │   └── BRATS_003.nii.gz
    │   │   ├── model_pretrained.hdf5 
    │   │   └── processed
    │   │       ├── config.json
    │   │       ├── train
    │   │       │   ├── BRATS_009.nii.gz_10_x78_y33_z93.h5
    │   │       │   ├── BRATS_009.nii.gz_11_x21_y0_z68.h5
    │   │       │   ├── BRATS_009.nii.gz_12_x42_y77_z72.h5
    │   │       │   ├── ...
    │   │       │   └── BRATS_009.nii.gz_9_x15_y12_z97.h5
    │   │       └── valid
    │   │           ├── BRATS_119.nii.gz_10_x23_y50_z73.h5
    │   │           ├── BRATS_119.nii.gz_11_x51_y51_z81.h5
    │   │           ├── BRATS_119.nii.gz_12_x63_y48_z89.h5
    │   │           ├── ...
    │   │           └── BRATS_119.nii.gz_9_x24_y63_z72.h5
    │   │
    │   ├── Brain\ Tumor\ Auto-Segmentation\ for\ Magnetic\ Resonance\ Imaging\ (MRI).ipynb
    │   └── util.py
    └── lectures
        └── AI4M_C1_W3_lecture.ipynb

15 directories, 63 files
```


## Assignments 

|  | Notebook | Description |
| --- | --- | --- |
| <img src="https://drive.google.com/uc?export=view&id=1AcG1bYX8fUXC_ejAGBmpYFhVkah6YUu-" width="300px" /> | [Chest X-Ray Medical Diagnosis with Deep Learning.ipynb](https://github.com/codeamt/AI4M/blob/master/AI%20for%20Medical%20Diagnosis/week_1/assignment/Chest%20X-Ray%20Medical%20Diagnosis%20with%20Deep%20Learning.ipynb) | Explores medical image diagnosis by building a pipeline for a state-of-the-art chest X-ray classifier using Keras. Phases of the pipeline includes Data preparation, model development, and evaluation. |
| <img src="https://drive.google.com/uc?export=view&id=1d3IoUPokhQDF8bzfknFlc9FyxhJiWfIB" width="300px" /> | [Evaluation of Diagnostic Models.ipynb](https://github.com/codeamt/AI4M/blob/master/AI%20for%20Medical%20Diagnosis/week_2/assignment/Evaluation%20of%20Diagnostic%20Models.ipynb) | Explores model evaluation and tabulating key metrics for medical diagnosis (e.g., Accuracy, Prevalence, Specificity & Sensitivity, PPV and NPV, ROC curve and AUCROC/c-statistic, Confidence Intervals). |
| <img src="https://drive.google.com/uc?export=view&id=1NTf_8Bl9IyAvIaKPCAEwRQoSKtBehPNV" width="300px" />  | [Brain Tumor Auto-Segmentation for Magnetic Resonance Imaging (MRI).ipynb](https://github.com/codeamt/AI4M/blob/master/AI%20for%20Medical%20Diagnosis/week_3/assignment/Brain%20Tumor%20Auto-Segmentation%20for%20Magnetic%20Resonance%20Imaging%20(MRI).ipynb) | You will learn how to build a neural network to automatically segment tumor regions in brain, using MRI (Magnetic Resonance Imaging) scans. This asssignment explores training a deep learning model for segmentation, learnings transferrable to other modalities (e.g., CXR, X-Rays, CTs, Ultrasound).|

<h1 align="center">
<img src="https://drive.google.com/uc?export=view&id=1ouxivsVkrre_tDX91Os6aBlibosvRl7s" width="70%" />
</h1>

