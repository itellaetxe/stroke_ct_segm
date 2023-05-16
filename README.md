# Stroke segmentation in CT
Little experiments to explore stroke segmentation methods in CT images.


## File Tree

```
stroke_ct_segm
 ┣ images
 ┃ ┣ fsl
 ┃ ┃ ┗ rigid_tac_1w_Tilt_1_moved_to_day_0.nii.gz (Week 1 image, rigid registration to Day 0)
 ┃ ┃
 ┃ ┣ skull_stripped
 ┃ ┃ ┣ rigid_tac_1w_Tilt_1_moved_to_day_0_skst.nii.gz (Moved Week 1 image, skull stripped)
 ┃ ┃ ┣ tac_0d_Tilt_1_skullstripped.nii.gz (Original Day 0 image, skull stripped)
 ┃ ┃ ┗ tac_1w_Tilt_1_skullstripped.nii.gz (Original Week 1 image, skull stripped)
 ┃ ┃
 ┃ ┣ DiffImMultiply.nii.gz (Week1 * Day0)
 ┃ ┣ DiffImSubstract.nii.gz (Week1 - Day0)
 ┃ ┣ tac_0d_Tilt_1.nii.gz
 ┃ ┗ tac_1w_Tilt_1.nii.gz
 ┃
 ┣ notebooks
 ┃ ┗ difference_region.ipynb   (Go to the "1) FSL Registered Images" section. The previous code is just some DiPy approach test)
 ┃
 ┣ README.md
 ┃
 ┗ utils
   ┗ synthstrip-docker (Wrapper script for skull-stripping using SynthStrip)
```
