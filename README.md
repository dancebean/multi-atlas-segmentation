multi-atlas-segmentation
========================

**Description**

This scriptis is created for "Multi-atlas based automatic brain structural parcellation" for mouse brain MRI.

For detailed description of the pipeline and to download the mouse brain parcellation atlas, please go the the website: http://cmic.cs.ucl.ac.uk/staff/da_ma/Multi_Atlas/


**Q/A**

- What image orientation should my test image be?
The orientation of the default atlas is: RAS. This script orient_nii.m uses the Matlab NIfTI toolbox (https://www.mathworks.com/matlabcentral/fileexchange/8797-tools-for-nifti-and-analyze-image) to visualize and determine the orientation, as well as reorient it. 

**Reference**

Ma, D., Cardoso, M. J., Modat, M., Powell, N., Wells, J., Holmes, H., … Ourselin, S. (2014). Automatic Structural Parcellation of Mouse Brain MRI Using Multi-Atlas Label Fusion. PLoS ONE, 9(1), e86576.
[http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0086576]