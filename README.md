# ML-Voice-Recognition - Miniproject for Machine Learning for Media Experiences
# By Karl-Emil Hald

Dataset Attribution and Licensing:

This processed version of the VocalSet: A Singing Voice Dataset is derived from the original dataset created by Wilkins et al. (2018) and made available under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. The original dataset can be accessed at [VocalSet: A Singing Voice Dataset](https://zenodo.org/records/1193957)

Modifications Made:

	• Silence removal using RMS energy threshold.
	• Amplitude normalization to [-1, 1] range.
	• Addition of Gaussian noise for data augmentation.
	• Reorganization of files: original features various folders sorted by technique. Since gender, not technique, was the focus for the project, subfolders are removed and files are structured as:
	• original: contains original unprocessed files (not used in project)
	• silence_removed_normalized: contains preprocessed files (used un the project)
	• unused: unused files due to poor labelling.
      

Original License:
The dataset is distributed under the CC BY 4.0 license, which permits sharing and adaptation for any purpose, even commercially, as long as the following conditions are met:
This processed version retains the original license and includes modifications by Karl-Emil Hald.
