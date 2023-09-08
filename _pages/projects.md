---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## Research projects
<hr>
### Quantum LDPC Decoders
&ndash; Developing software library in Julia for faster implementations and new modifications to Quantum LDPC decoders <br>
&ndash; Achieved 25% speedup for syndrome-based decoding of codes using belief propagation and bit-flip iterative algorithms

### Machine Learning for predicting atomic force fields in Platinum nanoclusters (Bachelor's Thesis)
&ndash; Developed atomic position-based Machine Learning (ML) models for predicting force fields of Platinum nanoclusters for the purpose of accelerating the Ab initio Molecular Dynamics (AIMD) computations <br>
&ndash; Generated force-field reference data by simulating Platinum environments; bulk, surface and nanoclusters using Gradient Generalized Approximation substitution in Density Functional Theory in VASP software <br>
&ndash; Implemented fingerprinting algorithm using a Radial Distribution Function for uniformity in numerical representations of the molecular environment unaffected by rotations or translations. <br>
&ndash; Handled non-linearities in the training data by transforming into higher dimensions using a Gaussian Kernel <br>
&ndash; Evaluated performance of ML models trained using Ridge Regression by 10-fold cross validation technique and through variance of environment data to assess generalizability and achieved MAE of 1-5% 

### Assisted Defect Recognition of Airplane castings
&ndash;	Developed Image Processing Algorithms for defect recognition in the torque arm of aircraft landing gear by analyzing their digital radiography images as part of Non-Destructive Evaluation <br>
&ndash;	Studied effects of different image filters on defective and defect-free images – convolution kernels, frequency domain filtering using Discrete Fourier Transform and binary thresholding, and documented the results <br>
&ndash;	Preprocessed raw DICOM images for noise reduction using combination of mean and Canny(Gaussian) filter <br>
&ndash;	Carried out defect segmentation by employing a BHPF and difference of gaussians, followed by a routine of image dilation and erosion to identify and quantify volume of shrinkages with a mean accuracy of 95% <br>

## Academic projects
<hr>
### Stock Trading System
&ndash; Developed a 3-tier stock trading server using Python that can maintain consistency between replicas upon failure <br>
&ndash; Implemented LRU caching at the top level and achieved a 20% decrease in mean latency of lookup requests 

### Elevation based Navigation system
&ndash; Built a navigation app using JavaScript and React to suggest the shortest route between 2 user defined locations <br>
&ndash; Implemented Dijkstra’s, A*, and BFS algorithms with elevation gain and achieved best performance with the first two

### Frequent pattern mining using Spark tweet streams
&ndash; Built Spark Streaming application for retrieving live tweets based on geographic origin using PySpark and Kafka <br>
&ndash; Implemented parallelized FP-growth to analyze frequent topics and associations in a 10-minute window in real-time
