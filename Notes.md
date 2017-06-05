# Notes
## Packages

### Update
```
conda update conda
```
Updates Anaconda

### Environments
#### Creating
```
conda create --name example-name example-packages
```
#### Activating
```
source activate example-name
```

To specify python version when creating environment, use
```
python=3.5
```

#### Listing Installed Environments
```
conda info --envs
```

#### Cloning environment
```
conda create --name example_name --clone cloned_name
```

#### Removing environments
```
conda remove --name environment_name --all
```
