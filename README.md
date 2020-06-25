# Julia-Scientific-Programming
Intro to Julia Programming Language offered by University of Cape Town via Coursera

## Install Julia
https://julialang.org/downloads/

#### If you want to use Julia in Jupyter Notebook, please follow the following instructions
#### (Suppose you already have Anaconda installed in your machie and created a conda virtual environment)

    conda install -c conda-forge jupyterlab
##### Then you have to open your julia shell (you should have Julia-1.4 installed and stored in your Application folder if you are using MacBook or other Apple computers)
##### Type the following code in Julia Shell

    using Pkg
    Pkg.add("IJulia")
    using IJulia
    
##### In your terminal shell, type the following commands

    conda activate /path/to/your/conda/virtual/environment/
    jupyter lab

##### It will automatically open the browser with Jupyter Notebook online, and you have to select Julia as the compling progamming language, and create a new jupyter notebook file to start your julia programming interactively.

