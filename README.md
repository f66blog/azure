# Jupyter Fortran Kernel for MS Azure

Need to set path for Python in kernel.json.

```
  "argv": [
      "/home/nbuser/.local/share/jupyter/kernels/python3/python3_path.sh",
```

## Install

### from Terminal

```
git clone https://github.com/f66blog/azure
jupyter kernelspec install azure/jupyter-gfort-kernel/gfort_spec --user
```

### from Python3 cell

```
import sys
!{sys.executable} -m pip install  -e ../azure/jupyter-gfort-kernel --user
```


## references
- https://jakevdp.github.io/blog/2017/12/05/installing-python-packages-from-jupyter/

- https://github.com/f66blog/jupyter-ifort-kernel
