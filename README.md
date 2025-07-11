# Matplotlib and pyplot

Complete the tasks in the Python Notebook in this repository.
To be submitted for credit, all changes must be committed and pushed to this repository (do not create your own repository unless instructed to on the course website).

## Rubric

Each question is worth two points: 

* Data plotted as described by the question (1 pt)
* Plot contains required elements (title, axis labels, axis titles, legend if required)

## Exporting Jupyter Notebook
1. Select Jupyter Notebook you wish to export
2. Click ellipses (...) in top menu
3. Select Export
4. Choose where to export to
5. Can use Live Server in VSCode to view new HTML file on local, right click HTML file and select 'Open with Live Server'

**Create virtual environment**
```shell
py -m venv .venv
```
**Activate virtual environment**
```shell
./.venv/Scripts/Activate
```
**Install Dependencies**
```shell
py -m pip install --upgrade pip setuptools wheel
py -m pip install -r requirements.txt
```
**Running**

After activating virtual environment, use following command template to run in terminal.

```shell
py ./[script name]
```
To run in Jupyter notebook, click Kernel (top right) > Python environments > virtual environment. You can then run each cell (or all) in Jupyter notebook.