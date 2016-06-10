This repository document's Mark's and Beckie's adventures into integrating
micromagnetic problems with Assimulo (in time) and Dolfin (in space).

##Installing assimulo on conda
Note, the most recent version of Assimulo (1.9) doesn't seem to work, so we use assimulo version 1.8 instead.

To create conda environment, the following commands are required:

conda create --name assimulo -c ufechner assimulo

source activate assimulo

conda install -c chria assimulo=2.8

conda install jupyter

conda install --yes libgfortran=1
