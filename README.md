# datafun-06-eda
Project 6 is an opportunity to create your own custom exploratory data analysis (EDA) project using GitHub, Git, Jupyter, pandas, Seaborn and other popular data analytics tools.

CC6.1: Start a New Project

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

CC6.2: Choose a Data Source

>I chose the palmerpenguins dataset since it is a built in library for python. The UCI Machine Learning Repository said it has no missing data values.
>
>![dataset image](https://allisonhorst.github.io/palmerpenguins/reference/figures/lter_penguins.png)
>“Artwork by @allison_horst”
>
>Description: The goal of palmerpenguins is to provide a great dataset for data exploration & visualization, as an .alternative to iris. Data were collected and made available by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER, a member of the Long Term Ecological Research Network. Data comes from 3 penguin species in the islands of Palmer Archipelago, Antarctica.
>[dataset csv link](https://github.com/Bdowdle4/datafun-06-eda/blob/main/data.csv)

P6 Exploratory Data Analysis

+ Start a notebook
+ Implement your custom EDA
+ Collaborate and complete your project

### Start Jupyter

```shell
#Example VS Code - in your project folder
code .
ni "filename.ipynb" #the file extension must be exactly ".ipynb" to open in jupyter
#Example Native Terminal - in your project folder
cd filename ##keep doing this until you reach the correct folder
jupyter lab #this command will also open in VS Code
```

### Steps to implement custom EDA

> Data Acquisition
>
> Initial Data Inspection
>
> Initial Descriptive Statistics
>
> Initial Data Distribution for Numerical Columns
>
> Initial Data Distribution for Categorical Columns
>
> Initial Data Transformation and Feature Engineering
>
> Initial Visualizations
>
> Initial Storytelling and Presentation

## Evaluation Criteria

- Functionality: The project should be functional and meet all requirements.
- Documentation: The project should be well-written and well-documented.
- Presentation: The project should be presented in a clear and organized manner.
- Professionalism: The project should be submitted on-time and reflect an original, creative effort.


## Resources

- See [datafun-04-spec](https://github.com/denisecase/datafun-04-spec) for a guided EDA.
- See [JUPYTER.md](https://github.com/denisecase/datafun-04-spec/JUPYTER.md) for Jupyter Notebook keyboard shortcuts and recommendations.
- See [MARKDOWN.md](https://github.com/denisecase/datafun-04-spec/MARKDOWN.md) for Markdown syntax and recommendations.
- See [Plotting graph For IRIS Dataset Using Seaborn And Matplotlib](https://www.tutorialspoint.com/plotting-graph-for-iris-dataset-using-seaborn-and-matplotlib)
- See [Seaborn Tutorial](https://seaborn.pydata.org/tutorial.html)
