# ProjectTemplate-PyWithNotebook

## Creating environment

Run the following in the project root to create an anaconda environment using ```environment.yml```:
```bash
conda env create -f environment.yml
```

## Activating environment

Run the following in the project root to activate the anaconda environment:
``` bash
conda activate [name environment]
```

## Listing environments

Run the following to list all available anaconda environments:
```bash
conda env list
```

## Export environment.yml

Run the following to export the active environment to ```environment.yml``` with only the packages that were explicitly specified:
```bash
conda env export --from-history
```

## Adding Jupyter Kernel

Run the following to add a kernel to Jupyter:
```bash
python -m ipykernel install --user --name="env" --display-name="Python (env)"
```

## Listing Jupyter Kernels

Run the following to list the kernels available to Jupyter:
```bash
jupyter kernelspec list
```

## Removing Jupyter Kernel

Run the following to remove a kernel from Jupyter:
```bash
jupyter kernelspec uninstall unwanted-kernel
```
