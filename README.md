# Data Analytics Tasks

## Repository Organization:
This repository is used to display tasks and projects completed during the semester for the University 
Data Analytics course. It showcases the skills acquired and applied throughout the duration of the course. <br>

Each task is organized into its own directory, which contains all the essential files, 
including dataset paths, and Jupyter notebook files with code implementations.

## Task Descriptions:
Detailed descriptions of each task, along with the necessary dependencies, 
are provided within the Jupyter notebook files in each project's directory. 
This information is located in the initial markdown blocks of the notebooks. <br>

## Sample Structure for Jupyter Notebook Files
Below is the template used for each Jupyter notebook within this repository <br>

**Task Name and General Description:**

```markdown
# Task Name
A brief description of the task.

## Dataset Used
Link to the dataset used in the task.

## Dependencies
A list of necessary Python packages and their versions.
```

**Installation Commands:** <br>
These commands are provided in a commented format, 
as they need to be run only once at the beginning of the code.
```jupyter
# !pip install pandas==2.2.1
# !pip install numpy==1.26.4
```

**Detailed Task Description:**
```markdown
## Task Description:

* Bullet point 1 explaining the project.
* Bullet point 2 explaining the project.
```

**Code Implementation with Descriptive Blocks:** <br>
For every significant portion of the task implementation, a markdown block explains the purpose and approach, followed by the actual code snippet.

```markdown 
## Description for the following task section
    * Key consideration or objective for this section.
    * Another relevant detail or consideration.
```
```jupyter
import pandas as pd

# example of loading the dataset
data = pd.read_csv('path/to/dataset.csv')
data.head()
```
