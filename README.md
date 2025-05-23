
# Weight Development in Pokémon

This project is the exam work for the course HEL-8048 (Advanced data analysis and visualization using programming) during the spring of 2025.

The project mainly looks at how the weight of different Pokémon has changes through the generations, and exploring the hypothesis that Pokémon follow the same trend as humans; getting thicker over the past decades. The [dataset](https://www.kaggle.com/datasets/rounakbanik/pokemon?resource=download) used is distributed by Rounakbanik on kaggle under the CC0 license.

## File overview

This repository contains several files, all of which are explained bellow.

`env.yml` Environment file containing all necessary dependencies

`exam.ipynb` Executable jupyter notebook file containing the exam work

`exam.html` HTML version of the jupyter notebook containing the exam work

`exam.pdf` PDF version of the jupyter notebook containing the exam work

`pokemon.csv` Collection of the Pokémon data used in the exam, [retrieved from kaggle](https://www.kaggle.com/datasets/rounakbanik/pokemon?resource=download)

`LICENSE` Includes the terms and conditions of the GNU General Public License

`decisions.pdf` PDF report that justifies the use of figure styles, reporting, and analysis.

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

You may need to add the conda environment to bashrc

```bash
conda init
```

Activate conda environment

```bash
conda activate hel8048
```

You can now open `exam.ipynb` in your jupyter notebook editor of choice and run all cells.

## Required Python Packages

To run this project, you will need to add the following python packages

`numpy` (Version 2.2)

`matplotlib` (Version 3.10)

`kagglehub` (Optional, version 0.3)

`ipywidgets` (Version 8.1)

`seaborn` (Version 0.13)

`pandas` (Version 2.2.3)

## Authors

- [@ylvao](https://www.github.com/ylvao)


## How to contribute

All contributions are appreciated! Whether it’s fixing a bug, improving the docs, or suggesting a new feature. This can be done by forking the project and opening a pull request.

## How to cite

```tex
@misc{
    title = {Weight Development in Pokémon}
    authour = {Ylva Os}
    year = {2025}
    url = {https://github.com/ylvao/HEL-8048}
}
```
