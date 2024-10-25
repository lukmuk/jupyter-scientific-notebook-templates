# Jupyter Scientific Notebook Templates
 Jupyter notebook templates for science projects.


## Environment Creation
`mamba` is used here but can be exchanged with `conda`.\
Change `ENV_NAME` below to your desired environment name.

```code
mamba create -n ENV_NAME python=3.12
```
```code
mamba activate ENV_NAME
```

Install *basic* packages:
```
mamba install -c conda-forge jupyterlab numpy matplotlib scienceplots watermark ipympl 
```

