# CaptionFool

Code repository for the MLsec project: 
CaptionFool: Fooling Image Captioning Models

Download this data folder: https://drive.google.com/drive/folders/1q6E8K4NvLSY-wb8G5vIKhQxAn1aCKQIe?usp=sharing

Installation: 
```
git clone https://github.com/salesforce/LAVIS.git
%cd LAVIS
pip install .
```

Code Files and Instructions: 

`patch_fool_universal_blip_overall.ipynb` : Patch-wise attacks on all prompt and patch combinations. Computes and stores Validation + Test Accuracy and attacked images+captions.

`patch_fool_universal_blip_sparse.ipynb` : Sparse Patch fool attack
