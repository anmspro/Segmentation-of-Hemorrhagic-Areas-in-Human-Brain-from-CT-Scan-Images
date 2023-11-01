# Segmentation-of-Hemorrhagic-Areas-in-Human-Brain-from-CT-Scan-Images
Brain hemorrhage is potentially a fatal condition that results from internal bleeding in the human brain. In this study, Computed Tomography (CT) scan images have been used for segmentation tasks to pinpoint the area of hemorrhage. Unique data augmentation techniques using non-linear transformations like, Twirl and Spherical have been used along with traditional data augmentation techniques to increase variation in the dataset. The hemorrhagic portion of the brain in images that are easy to distinguish have been annotated to perform the segmentation task. The segmentation task was applied using U-Net and U-Net++ architecture. U-Net architecture has shown 84.33% Intersection over Union (IoU) and 91.34% dice coefficient score whereas U-Net++ has achieved 17.06% IoU and 28.27% dice coefficient score after applying some non-linear transformations on the dataset.

# The dataset link can be found in here: https://www.kaggle.com/datasets/felipekitamura/head-ct-hemorrhage

# Paper link can found in here: https://ieeexplore.ieee.org/abstract/document/10103333
