# AIM-CCReID
An official implement of 《Good is Bad: Causality Inspired Cloth-Debiasing for Cloth-Changing Person Re-Identification》

The testing and evaluation code, with the corresponding weights, are released for review.

The full training code will be released once it has been accepted. 

## Datasets
PRCC is avaiable at https://drive.google.com/file/d/1yTYawRm4ap3M-j0PjLQJ--xmZHseFDLz/view  

LTCC is avaiable at https://naiq.github.io/LTCC_Perosn_ReID.html

## Testing
The trained models (weights) are avaiable at https://pan.baidu.com/s/1Du1XgoCim6I_bZtNRm3yPw?pwd=v4ly 
code: v4ly 

You will find the testing script for prcc and ltcc at `test_AIM.sh`, then modify the resume path to your own path where you placed the weights file.  

To be noticed, you need to modify the `DATA ROOT` and `OUTPUT` in the `configs/default_img.py` to your own path before testing.


