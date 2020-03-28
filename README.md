# Useful resources 

## Conda environments
[All about environments](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#viewing-a-list-of-your-environments)

### To see a list of all of your environments, in your terminal window or an Anaconda Prompt, run:
```
conda info --envs
```
OR
```
conda env list
```

### **To get jupyter to use your conda environment:**
```
python -m ipykernel install --user --name=py36
```
where `py36` is the name of my conda environment
* Launch Jupyter notebook and select your environment from the list of kernels. 
