# IntroJupyterLab

Supporting files from a short talk on Jupyter Lab.

4/14/2020 cgates


### To run BasicJupyterNotebook.ipynb:

1. Clone this repo.

2. Establish conda environment
   
   Download and install conda:
https://docs.conda.io/en/latest/miniconda.html


```
$ conda env create -f envs/jupyterlab.yaml
$ conda activate jupyterlab
```

3. Launch Jupyter Lab  
```$ jupyter lab```  
This will automatically spawn a new browser tab with a new workspace. You can exit by closing the tab and ctrl-C to stop the notebook server in the terminal. (The server process will prompt you to confirm.)

_Incidentally, you can always launch the "classic" notebook interface by typing:  
```$ jupyter notebook```_

---