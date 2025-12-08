# Workflow management and sharing with Nextflow and nf-core
Managing bioinformatics workflows (e.g. sequencing analysis pipeline) is a central problem for many of us. Simple bash scripts are maybe easy to write, but hard to run and maintain. Snakemake is a good solution for reproducibility and automation, but it is hard to reuse its components. Nextflow is a workflow manager tool like Snakemake, but solves those problems too that make Snakemake sometimes difficult to run. The price to pay is that getting into Nextflow might be hard. Here, we would like to reduce the initial time investment and help you understand the main concepts while you try building a small pipeline.

## Instructors
Katalin Ferenc, Villads Winton

## Live Troubleshooting Session

## Software Requirements

Nextflow and nf-core to be installed.

To clone this repository:

```bash
git https://github.com/OBIWOW/OBiWoW-2025.git

cd OBiWoW-2025
```

```bash

## install nextflow and nf-core
curl -s https://get.nextflow.io | bash
echo $PATH
# depending on what is in your PATH, you can move nextflow executable there
# mv nextflow /usr/bin
# if you already have nextflow installation, move the newly installed version to the folder in the beginning of PATH
nextflow -v
nextflow -h

pip install nf-core
nf-core -h

```

More Nextflow instructions are here:

```bash
https://www.nextflow.io/docs/latest/install.html
```

More nf-core instructions are here:

```bash
https://nf-co.re/docs/usage/getting_started/introduction
```
