# Atividade Pratica 07

## Pre-requisitos
- Python 3.10+, Git e DVC 3

## DVC Storage
```bash
dvc remote add -d storage ../dvc-storage
```

## Restauracao
```bash
git clone https://github.com/MatheusAlvesCavalcante/aula-ml.git aula-ml-restauracao
cd aula-ml-restauracao
git switch --detach modelo-r1
dvc pull
```
