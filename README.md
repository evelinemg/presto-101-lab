# Presto Workshop

## Participação no Workshop no dia 07/02/2024
### Edit: Inclui um arquivo docker-compose.yaml para facilitar o steup do ambiente
Para inicializar o ambiente pelo docker composer basta entra na pasta pelo terminal e colar a linha de comando:
```
docker-compose -f docker-compose.yaml up -d
```
---
This is a repo that hosts the materials for the Presto workshop. You can view the workshop
[here](https://ibm.github.io/presto-101-lab/)

Here is the file structure of this repo:
```ini

- data (any data (CSV, JSON, etc files) to be used)
- docs (this is where the workshop is documented)
|_ <folder-n> (these are exercises for the workshop)
  |_README.md (the steps for the exercise, in Markdown)
|_ README.md (this will appear on the gitbook home page)
- notebooks (any Jupyter notebooks can go here)
- src (any application source code can go here)
.mkdocs.yaml (configuration for mkdocs)
.travis.yaml (runs markdownlint by default)
README.md (only used for GitHub.com)
```

## Authors
- Yihong Wang yh.wang@ibm.com

