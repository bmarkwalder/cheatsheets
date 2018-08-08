# Anaconda

Anaconda is a package manager that works especially well on Windows machines. Python packages are installed at the base level, or into specifically crafted environments.

### Updating conda and packages
- Update conda to the current version   
```cond update conda```
- Install a package included in Anaconda  
````conda install PACKAGENAME````
- Update any installed program  
```conda update PACKAGENAME```

### Creating and managing environments
- Create a new environment named red_winged_blackbird  
```conda create --name red_winged_blackbird python=3.6```
- Activate the new environment  
```activate red_winged_blackbird```
- List environments (active environments are shown with a *)  
```conda env list```
- Copy an environment  
```conda create --clone red_winged_blackbird --name pickled_herring```
- List all packages in the active environment  
```conda list```
- Save an environment to a text file  
```conda list --explicit > red_winged_blackbird.txt```
- Create and environment from a text file  
```conda env create --file red_wingerd_blackbird.txt```
- Delete an environment and everything in it  
```conda env remove --name red_winged_blackbird```

### Installing and updated packages
- Install a new package in the active environment  
```conda install PACKAGENAME```
- Install a package directly from PyPl into the current environment using pip  
```pip install PACKAGENAME```

## References:

- [Conda Cheat Sheet](https://conda.io/docs/_downloads/conda-cheatsheet.pdf)