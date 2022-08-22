# Algorithme-MICO
"Multiplicative intrinsic component optimization (MICO) for MRI bias field estimation and tissue segmentation", Magnetic Resonance Imaging, vol. 32 (7), pp. 913-923, 2014   Author: Chunming Li, all rights reserved E-mail: li_chunming@hotmail.com URL:  http://imagecomputing.org/~cmli/


Usage for 3D MICO
Input: 
      images in nifti format.
Output: 
      The results of segmentation and bias field correction in two files in nifti format: the       
      segmented image and the bias field corrected image are saved as nifti files with postfixes       
      "_seg" and "_bc", respectively. 

Note: For visualization, the code only shows the result for one of the 2D slices, although it performs 3D segmentation and bias field estimation/correction.
   
