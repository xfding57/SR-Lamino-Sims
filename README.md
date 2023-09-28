# SR-Lamino-Sims
Simulations for computed laminography

## Part 1 - Make phantom  
Using Part1_makephantom.m in MATLAB, make an object resembling a resolution phantom. The structure of the phantom doesn't necessarily have to resemble any real object. Define the padding, laminography angle, and the rotation steps. The padding helps determine the field of view (FOV). If there is no padding or if the padding is too small, the edges of the phantom may rotate out of the FOV. For each angular step, a .txt file containing the phantom will be created. This will be read in Part 2.



## Part 2 - Forward project
Using Part2-astra-CT-230226.py. Forward project each .txt file from Part 1 to create a laminography dataset.

![Forward Project](https://github.com/xfding57/SR-Lamino-Sims/blob/main/media/n_grid-500-CL-736x622)


## Laminography Reconstruction