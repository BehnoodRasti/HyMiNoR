# HyMiNoR
Hyperspectral Mixed Gaussian and Sparse Noise Reduction
This is a Two Step Mixed Noise Removal Technique for Hyperspectral Images.
Please cite the following paper
B. Rasti, P. Ghamisi and J. A. Benediktsson, "Hyperspectral Mixed Gaussian and Sparse Noise Reduction," in IEEE Geoscience and Remote Sensing Letters. % doi: 10.1109/LGRS.2019.2924344 % % % If your data is not scaled between [0 1] you can use X_N=Normalization(X) % to scale the data between [0 1]. % First the Gaussian noise is removed using the "HyRes" technique which is also provided along with the codes for Wavelab fast toolbox Problem formulation to solve the sparse noise is: min_(x) ||H-X||_1+ lambda ||X*D'||_1, where D is the difference matrix.
