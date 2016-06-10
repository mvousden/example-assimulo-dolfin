This repository document's Mark's and Beckie's adventures into integrating
micromagnetic problems with Assimulo (in time) and Dolfin (in space).

##Requirements
Note, the most recent version of Assimulo (2.9) doesn't seem to work, so we use
Assimulo version 2.8 instead.

To create conda environment, the following commands are required:

conda create --name assimulo-dolfin --channel ufechner assimulo
source activate assimulo-dolfin
conda install --channel chria assimulo=2.8
conda install jupyter
conda install libgfortran=1
conda install hdf5
conda install boost=1.57
conda install vtk=5.10
conda install mkl-rt
conda install fenics --channel juanlu001
conda install petsc=3.6 --channel juanlu001
pip install git+https://github.com/fangohr/dolfinh5tools

You might need to instant-clean.