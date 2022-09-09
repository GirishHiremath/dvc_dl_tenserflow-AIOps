# DVC -DL  -TF - AIOPS 

## comands

## create a new env
```bash
conda create -prefix ./env python=3.7 -y
```

## activate new env
```bash
conda activate ./env
```

## init git
```bash
git init
```

## init dvc
```bash
dvc init
```

### create empty files -
```bash
mkdir -p src/utils config
touch dvc.yaml setup.py README.md src/__init__.py src/utils/__init__.py params.yaml congif/config.yaml .gitignore
```

## install src
```bash
pip install -e .

```

