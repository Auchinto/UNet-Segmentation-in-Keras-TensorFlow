# Brain Tumor Semantic Segmentation using UNet architecture

## Dataset
Link: <a href="https://figshare.com/articles/brain_tumor_dataset/1512427/5">Brain Tumor Dataset</a>
Obtain the images of Brain MRI slices across different planes and corresponding binary masks to identify region in the slice signifying presence of tumor.

## Procedure
1. Download (.zip) from the above link. The data set will be in terms of (.mat) files, comprising of 'PID', 'label', 'image', 'tumorBorder' and 'tumorMask'.
2. Use 'mat2png.ipynb' to generate the image of brain MRI slices and corresponding binary masks for those images, in (.png) format.
3. Store the files such that, the directory tree is as follows:

# /dataset/brainTumorData/1/images/1.png - image for 1.mat
# /dataset/brainTumorData/1/masks/1.png - mask for 1.mat

