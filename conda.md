# Anaconda

Anaconda is a package manager that works especially well on Windows machines. Python packages are installed at the base level, or into specifically crafted environments.

### Updating conda and packages
- Update conda to the current version   
```conda update conda```
- Check the version of an installed package
```PACKAGENAME --version```
- Install a package included in Anaconda  
````conda install PACKAGENAME````
- Update any installed program  
```conda update PACKAGENAME```
- Upgrade any installed program
```conda upgrade PACKAGENAME``` for example ```conda upgrade python```

### Creating and managing environments
- Create a new environment named redwingedblackbird
```conda create --name redwingedblackbird python=3.7.1```
- Activate the new environment  
```activate redwingedblackbird```
- List environments (active environments are shown with a *)  
```conda env list```
- Copy an environment  
```conda create --clone redwingedblackbird --name pickled_herring```
- List all packages in the active environment  
```conda list```
- List the history of each change to the current environment
```conda list --revisions```
- Restore environment to a previous version
```conda install --revision 2```
- Save an environment to a text file  
```conda list --explicit > redwingedblackbird.txt```
- Create an environment from a text file
```conda env create --file redwingerdblackbird.txt```
- Delete an environment and everything in it  
```conda env remove --name redwingedblackbird```
- Deactivate the current environment
```deactivate```

### Installing and updating packages
- Install a new package in the active environment  
```conda install PACKAGENAME```
- Install a package directly from PyPl into the current environment using pip  
```pip install PACKAGENAME```
- Update a package in the current environment
```conda update PACKAGENAME```

## References:

- [Conda Cheat Sheet](https://conda.io/docs/_downloads/conda-cheatsheet.pdf)