
# Weight Development in Pokémon

This project is the exam work for the course HEL-8048 (Advanced data analysis and visualization using programming) during the spring of 2025. 

The project mainly looks at how the weight of different Pokémon has changes through the generations, and exploring the hypothesis that Pokémon follow the same trend as humans; getting thicker over the past decades.

## File overwiew

This repository contains several files, all of which are explained bellow.

`env.yml` Environment file containing all necessary dependencies

`exam.ipynb` Executable jupyter notebook file containing the exam work

`exam.html` HTML version of the jupyter notebook containing the exam

`pokemon.csv` Collection of the Pokémon data used in the exam, [retrived from kaggle](https://www.kaggle.com/datasets/rounakbanik/pokemon?resource=download)

`LICENCE` Includes the terms and conditions of the GNU General Public Licence

`decicions.pdf` PDF report that justifies the use of figure styles, reporting, and analysis.

## Run Locally

The project can be installed via git to be ran locally using the following the instructions bellow.

Clone the project using the command

```bash
git clone https://github.com/ylvao/HEL-8048
```

Go to the project directory

```bash
cd HEL-8048
```

Install conda environment with the required python packages

```bash
conda env create -f env.yml
```

Activate conda 

```bash
conda activate hel8048
```

## Required Python Packages

To run this project, you will need to add the following python packages

`numpy` (Version 2.2)

`matplotlib` (Version 3.10)

`kagglehub` (Optional, version 0.3)

`ipywidgets` (Version 8.1)

`seaborn` (Version 0.13)

`pandas` (Version 2.2)


## Authors

- [@ylvao](https://www.github.com/ylvao)

