# GITM_1D_ModelCodes

Tar zip file containing the GITM 1D Run codes

Take this archive and unzip witht the following tar -xzf 1DGITM.tgz

Pick a directory on your machine and do the following:

Use these commands to install GITM

> ./Config.pl -install -Titan -compiler=gfortran
> make clean
> make
> make rundir

This should create a run directory where you can run the model using ./GITM.exe 

