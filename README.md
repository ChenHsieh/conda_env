# some conda_env

```bash
# create conda environment with yaml file 
conda env create -f file_name.yml
# activate the env, env_name is specified in the yaml file
conda activate env_name
# after some mod, use this to create your own env.yaml
conda env export > environment.yml
```

