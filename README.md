# neuroprint-validation

The purpose of the study is to validate the efficacy of Neuroprint, [a software pipeline](https://github.com/willtack/neuroprint-pipeline) which calculates and graphically renders deviations in regional cortical thickness from values observed in healthy control subjects. Specifically, the aim is to demonstrate that Neuroprint-rendered images (aka heatmaps) improve diagnostic accuracy of different types of neurodegenerative disease, including Alzheimer’s Disease (AD) and fronto-temporal dementia (FTD), and their subtypes compared to the corresponding unprocessed T1w MRI image in a clinical setting. A secondary objective is to show Neuroprint renderings improve reader classification of disease cases versus healthy controls.

## website

https://willtack.github.io/neuroprint-validation/

This website is the home for all the data and surveys needed for reviewers. 

## code

The code/ directory contains code needed to organize the data for this study. 

This includes 

- creating a dedicated [Flywheel project](https://upenn.flywheel.io/#/projects/60fef55e60ec55d1b0e0741e) with the appropriate data
- running the Neuroprint gear
- downloading heatmap images and T1w niftis
- scripting the creation of html pages from T1w niftis
- automatically populating stage2.md with image links
- randomizing the order and labels of images for the various stages of this study

