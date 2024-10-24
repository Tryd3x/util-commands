This repository is primarily for storing CL/CI commands for future references


## **Conda**

To install conda environment in current path, do:

`conda env create -p <name_of_environment> -f <environment_file>.yml`

To update environment.yml, do:

`conda env export --no-builds -p <name_of_environment> > environment.yml`

Remove conda environment, do:

`conda remove -p <name_of_environment> --all`
