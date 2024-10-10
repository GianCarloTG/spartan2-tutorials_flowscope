## Live-tutorials: Table of Contents



Spartan has compatibility issues with python3.11, to run the code we generate a new kernel

```
conda create --name myvenv python=3.10
activate myvenv
pip install ipykernel
python -m ipykernel install --user --name py310
```
A new kernel in the jupyter notebook will be avialable
Select kernel py310 and import the spartan modules

```bash
   # install spartan using pip
   pip install spartan2
```
```python
   # import spartan package
   import spartan as st
```
