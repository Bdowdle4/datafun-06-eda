# datafun-06-eda
Project 6 is an opportunity to create your own custom exploratory data analysis (EDA) project using GitHub, Git, Jupyter, pandas, Seaborn and other popular data analytics tools.

## How to Install and Run the Project

### Clone Your Repo

```shell
git clone "paste_your_repo_URL_here"
```

### Create Project Virtual Environment

On Windows, create a project virtual environment in the .venv folder. 

```shell
py -m venv .venv
.venv\Scripts\Activate
pip list
py -m pip install --upgrade pip
deactivate
```

### Create files in root folder

```shell
# Example for managing project requirements
code .
ni "requirements.txt"
```

### Add all dependencies by installing packages seperately
```shell
#Example If you have a requirements.txt list each package in this file
py -m pip install -r requirements.txt
#Example If you don't
py -m pip install jupyterlab numpy pandas matplotlib seaborn scipy
```

### Freeze Your Dependencies
This will keep the package at the version it was installed as
```shell
py -m pip freeze > requirements.txt
```

### Git add and commit 

```shell
git add .
git commit -m "initial commit"
git push origin main
```