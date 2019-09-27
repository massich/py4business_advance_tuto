# Some advance materials and tutorials for python for business

This material has been adapted from:

- hypothesis: https://github.com/Zac-HD/escape-from-automanual-testing
- Performance with cython: https://github.com/jeremiedbb/tutorial-euroscipy-2019
- more cython and numba: https://github.com/pierreablin/python-sessions


### Installing dependencies at once using conda
You can get a ready-to go environment by cloning the repo and running:
```
conda env create
```
and then:
```
conda activate performance-tutorial
```

## Speed up your Python code

### Requirements
- python >= 3.5
- jupyter
- numpy
- scipy
- cython
- numba
- snakeviz
- pandas
- matplotlib


- a C compiler supporting OpenMP
  (for macOS users: ``conda install gcc``)

### Binder
You will be required to have an internet connection but you will not have to
install any package locally.
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jeremiedbb/tutorial-euroscipy-2019/master?filepath=tutorial.ipynb)

