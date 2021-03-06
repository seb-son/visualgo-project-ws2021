# Visual Analytics Lab Project 2020/21
Submission template for the Visual Analytics lab project at the Johannes Kepler University Linz.

**Explanation:**
This `README.md` needs to be updated and pushed to github for the first and the final deadline.
Change/extend the corresponding sections by replacing the [TODO] markers.
*In order to meet the deadlines make sure you push everything to your Github repository.*
For more details see [Visual Analytics Moodel page](https://moodle.jku.at/jku/course/view.php?id=15596).

**Tip:** Make yourself familiar with [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

## General Information
*Due on 07.12.2021.*

### Group Members

| Student ID    | First Name  | Last Name      | E-Mail | Workload [%]  |
| --------------|-------------|----------------|--------|---------------|
| [51902760]    | [Jacqueline]| [Wipplinger]   |[jacqueline.wipplinger@outlook.com]   |
| [12021216]    | [Nicolas]   | [Madella-Mella]|[nicolas.madellamella@gmail.com]      |[TODO]         |
| 1246236     | Sebastian | Sonderegger   |s.sonderegger@mailbox.org           |[TODO]         |
| 11915448        | Manuel      | Karlsberger         |manuel.karlsberger@gmx.at  |[TODO]         |

### Dataset

* What is the dataset about?
    * Stroke Prediction Dataset
* Where did you get this dataset from (i.e., source of the dataset)?
    * https://www.kaggle.com/fedesoriano/stroke-prediction-dataset



## Usage

### Locally
Checkout this repo and change into the folder:

```shell
git clone https://github.com/jku-icg-classroom/va-project-2021-group-unhealthy.git
cd va-project-2021-group-unhealthy
```

Load the conda environment from the `environment.yml` file, if you haven't already in previous assignments:

```sh
conda env create -f environment.yml
```

Activate the loaded conda environment:

```sh
conda activate python-tutorial
```

Install Jupyter Lab extension to use *ipywidgets* in JupyterLab:

```sh
jupyter labextension install @jupyter-widgets/jupyterlab-manager
```

Launch Jupyter :

```shell
jupyter lab
```

Jupyter should open a new tab with url http://localhost:8888/ and display the tutorial files.


## Final Submission
*Due on 17.01.2022.*

* Make sure that you pushed your GitHub repository and not just committed it locally.
* Sending us an email with the code is not necessary.
* Please update the *environment.yml* file if you need additional libraries, otherwise the code is not executeable.
* Save your final executed notebooks as html and add them to your repository.  
  Select 'File' -> 'Export Notebook As...' -> 'Export Notebook to HTML'
