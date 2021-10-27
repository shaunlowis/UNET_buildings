# UNET_buildings
My implementation of using the UNET model to identify buildings in satellite imagery:
<img width="684" alt="unet" src="https://user-images.githubusercontent.com/63687545/139163518-d6861a58-58a2-4c01-88cb-7338d83fa8c1.png">

For now the code remains mostly undocumented, but if you are greatly interested, the project report that I have written
for the development and methodology behind my model for my PHYS381 lab course is included.

This project was started for developing a method of quantifying urban expansion of cities. This will continue in development
in the near future, as a deliverable software package to end-users.

Some overviews and quick guide to understanding a confusion matrix:
The code for the model itself is in UNET.ipynb. The trained model is in the model.h5 file.
Other files in this repo was used as utilities for pre-processing model input.
The paper outlining the model and methodology is titled PHYS381_project_report.pdf.

An analysis of the confusion matrix:
![confusion_matrix_interp](https://user-images.githubusercontent.com/63687545/139163463-08b052d2-e2c4-49a3-ad73-2aef6685c251.png)

