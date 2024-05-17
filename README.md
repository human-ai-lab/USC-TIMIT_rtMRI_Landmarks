# USC-TIMIT_rtMRI_Landmarks
Landmarks Dataset for rtMRI USC-TIMIT

There are version available in this dataset

Version 1:
- This dataset is the result of the paper "Refining rtMRI Landmark-Based Vocal Tract Contour Labels with FCN-Based Smoothing and Point-to-Curve Projection"
- It consist of F1 and F5 dataset from the contour with 180-format points
- This dataset only refine the data that are available in the original dataset

Version 2:
- This dataset is the result of applying the method in the paper "Refining rtMRI Landmark-Based Vocal Tract Contour Labels with FCN-Based Smoothing and Point-to-Curve Projection", to all available contour data after all all available format points are converted to 180-format points
- The result of the refinement are available for subjects F1, F5 and M3.
- For the other subject, a tranformation is applied to the video frame so FCN can output the contour data with less error.
- For the other subject, as the contour data are not the refinement of the original data, it still contain many inaccuracies that will be addresed in the future version.
