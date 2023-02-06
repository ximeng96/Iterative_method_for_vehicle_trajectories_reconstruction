# An iterative method for correcting and smoothing vehicle trajectories based on first principles

The dataset includes processed trajectory data of vehicles moving at the NGSIM I80 site during 4:00pm to 4:15pm. We focus on the longitudinal vehicle trajectories and offer an iterative method to reconstruct them.

#  Method application with the NGSIM data
## Calibration with sample trajectories on freeways and urban arterials
To replicate the samples, the codes are available at "codes -> ite_method", and the data are available at "codes -> sample_data". Note that due to the limitation of the file size in Github, "sample_data" only include part of the trajectories. However, the entire NGSIM dataset can also be used for testing our code, which can be downloaded at https://data.transportation.gov/Automobiles/Next-Generation-Simulation-NGSIM-Vehicle-Trajector/8ect-6jqj.

Or the code can be tested via JupyterLite at
https://ximeng96.github.io/Iterative_method_for_vehicle_trajectories_reconstruction/lab/index.html.

## Application to the NGSIM I80 dataset
The codes used for reconstructing the entire NGSIM I80 dataset are available at "codes -> ite_method_dataset". 

# The reconstructed data
The raw and the reconstructed data are avaliable at https://drive.google.com/file/d/1S5_ywtYxgo4tvalexLOxv_uUhuDZT2-Z/view?usp=sharing and https://drive.google.com/file/d/1bAtdnSZsqDBF75vP_fMb3r7LlabQR8lZ/view?usp=sharing

## Requirements

JupyterLite is being tested against modern web browsers:

- Firefox 90+
- Chromium 89+

## Deploy your JupyterLite website on GitHub Pages

Check out the guide on the JupyterLite documentation: https://jupyterlite.readthedocs.io/en/latest/quickstart/deploy.html

## Further Information and Updates

For more info, keep an eye on the JupyterLite documentation:

- How-to Guides: https://jupyterlite.readthedocs.io/en/latest/howto/index.html
- Reference: https://jupyterlite.readthedocs.io/en/latest/reference/index.html
