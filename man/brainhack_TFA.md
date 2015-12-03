<script type="text/javascript"
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
  </script>
  
#Topographic Factor Analysis

##Introduction
Functional Magnetic Resonance Imaging (fMRI) data sets contains multiple three-dimensional images, where each image reflects the activities of thousands of voxels. Instead of studying the individual voxels, researchers generally tend to look at the functionality of brain regions, which is composed of a number of voxels.


Topographic Factor Analysis (TFA) is the technique, which is first introduced by Manning, Jeremy R. et al,  for automatically discovering the brain regions based on learning lots of recorded images.


Pricinpal Component Analysis (PCA) and Independent Component Analysis (ICA) are two classical approaches in neouscience field. PCA is used to give factor set which explains the variance of observed data as large as possible, while ICA mainly gives distinct underlying features from observations. But, those approaches belong to matrix factorization, TFA is more flexible and it also gives simple spatial interpretation.  
##Approach
TFA is a factor model using a topographic basis composed of spherical Gaussian with different centers and widths. Because under TFA framework, it assumes that fMRI images reflect the activities of a finite number of sources distributed throughout the brain.
$\beta$
##Results
In this experiment, we applied TFA on fMRI data set by . This data set contains data from 9 participants with 360 images when they were showed all 60 drawings with 6 epochs, where all 60 drawings were randomly ordered. In this short hackthon time, we only explored the first participant's collection data.

##Discussion

##Conclusions.
