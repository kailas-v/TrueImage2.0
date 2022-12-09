# Development and clinical evaluation of an AI support tool for improving telemedicine photo quality

Data used for analysis in our paper, [***Development and clinical evaluation of an AI support tool for improving telemedicine photo quality***](https://arxiv.org/abs/2209.09105). In particular, the file, `clinical_study_data.csv`, contains the data used for our clinical study analysis.

There are 6 columns in this data. Images are graded on a A-F scale (A,B,C,D,F); the `Quality` columns translate this grade to a 0 to 4 scale as described in our paper -- 0-1 (A-B) are considered good quality and 2-4 (C-F) are considered poor quality and inadequate for clinical decisions. Reported quality values were averaged across based on ratings from 3 board-certified dermatologists. All columns are described below:

1. `Baseline Quality`: the quality of the first image submitted by the patient.
1. `TrueImage Quality`: the quality of the image selected by TrueImage 2.0.
1. `Best Quality`: the quality of the best image submitted by patients.
1. `Did TrueImage Terminate?`: boolean indicating whether TrueImage found a sufficient quality image; patients were allowed to submit at most 4 images.
1. `# Images Submitted`: the number of images the patient submitted.
1. `Extra Duration`: the duration in seconds taken by the patient after the first image was submitted.