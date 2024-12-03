# HR-Employee-Attrition

# P5-Building-Machine-Learning-APIs-With-FastAPI

![The image should showcase the integration of high ](https://github.com/bamzyyyy/HR-Employee-Attrition/blob/main/Image/Employee-Attrition.jpg)


## Project Overview 📖

In this project, we analyze employee attrition data and identify the key factors contributing to employee turnover. The insights aim to help HR departments proactively address issues, improve employee retention, and reduce costs associated with recruitment and training.

The HR Employee Attrition project focuses on analyzing employee data to uncover the factors driving workforce turnover and predicting potential attrition. By leveraging statistical analysis and machine learning models, the project identifies key variables such as job satisfaction, work-life balance, and compensation that significantly influence employee retention. The results are visualized through interactive dashboards, offering HR departments actionable insights to optimize employee engagement strategies and reduce attrition costs. This data-driven approach not only enhances decision-making but also helps organizations retain top talent and foster a more stable workforce.

**Benefits**
- HR Strategy Optimization:
Provide actionable insights to HR for designing employee engagement and retention strategies.

- Cost Reduction:
Lower recruitment and onboarding expenses by reducing turnover.

- Informed Decision-Making:
Use Dashboards to communicate findings.

**Key Features**

- Data Analysis:

Conduct in-depth analysis of employee data, including demographics, job roles, satisfaction levels, and compensation.
Identify trends and patterns associated with attrition.

- Visualization:

Use tools like Tableau and Matplotlib to create dashboards and visualizations.
Highlight critical insights such as departments with the highest attrition rates, influential factors, and predictions.

- Key Factors Assessment:

Analyze factors like job satisfaction, work-life balance, salary, promotion opportunities, and years at the company.
Rank these factors by their impact on attrition.


The project is guided by the CRISP-DM (Cross-Industry Standard Process for Data Mining) framework.

## Project Links :link:

| Notebook     | Published Article |
|-----------|:-------------:|
| [HR Employee Attrition notebook](https://github.com/bamzyyyy/HR-Employee-Attrition/blob/main/Notebook/HR_employee.ipynb) |  [Sepsis Prediction Article](https://medium.com/@aminuoluwarotimi/building-a-machine-learning-api-with-python-fastapi-and-docker-81ec608b9263) |


## Table of Contents 🔖
- [Project Overview](#project-overview-)
- [Project Links](#project-links-link)
- [Some Tools Used For The Project](#some-tools-used-for-the-project-hammer_and_wrench)
- [Dataset](#data-fields-)
- [Repository Setup](#repository-setup)
- [Run FastAPI](#run-fastapi)
- [API Screenshots](#fastapi-screenshots)
- [Author](#author-writing_hand)

##  Some Tools Used For The Project :hammer_and_wrench:
<p align="left">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" alt="vscode" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original-wordmark.svg" alt="pandas" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" alt="numpy" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="python" width="45" height="45"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original-wordmark.svg" alt="jupyter" width="45" height="45"/>
<img src="https://icongr.am/devicon/docker-original-wordmark.svg?size=45&color=currentColor" alt="docker"/>
</p>


## Data Fields 💾

| Column   Name                | Attribute/Target | Description                                                                                                                                                                                                  |
|------------------------------|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ID                           | N/A              | Unique number to represent patient ID                                                                                                                                                                        |
| PRG           | Attribute1       |  Plasma glucose|
| PL               | Attribute 2     |   Blood Work Result-1 (mu U/ml)                                                                                                                                                |
| PR              | Attribute 3      | Blood Pressure (mm Hg)|
| SK              | Attribute 4      | Blood Work Result-2 (mm)|
| TS             | Attribute 5      |     Blood Work Result-3 (mu U/ml)|                                                                                  
| M11     | Attribute 6    |  Body mass index (weight in kg/(height in m)^2|
| BD2             | Attribute 7     |   Blood Work Result-4 (mu U/ml)|
| Age              | Attribute 8      |    patients age  (years)|
| Insurance | N/A     | If a patient holds a valid insurance card|
| Sepssis                 | Target           | Positive: if a patient in ICU will develop a sepsis , and Negative: otherwise |

## Repository Setup

Install the required packages to be able to run the API locally.

You need to have [`Python 3`](https://www.python.org/) on your system. Then you can clone this repo and being at the repo's `root :: repository_name> ...`  follow the steps below:

- Windows:
        
        python -m venv venv; venv\Scripts\activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt  

- Linux & MacOs:
        
        python3 -m venv venv; source venv/bin/activate; python -m pip install -q --upgrade pip; python -m pip install -qr requirements.txt  

The two long command-lines have the same structure. They pipe multiple commands using the symbol ` ; ` but you can manually execute them one after the other.

1. **Create the Python's virtual environment** that isolates the required libraries of the project to avoid conflicts;
2. **Activate the Python's virtual environment** so that the Python kernel & libraries will be those of the isolated environment;
3. **Upgrade Pip, the installed libraries/packages manager** to have the up-to-date version that will work correctly;
4. **Install the required libraries/packages** listed in the `requirements.txt` file so that they can be imported into the python script and notebook without any issue.

**NB:** For MacOs users, please install `Xcode` if you have an issue.

## Author 👨‍💼

  | Name                                            | LinkedIn                                                                                                                                                                                                                                              
| ------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Aminu Oluwarotimi Desmond | [Aminu Oluwarotimi Desmond](https://www.linkedin.com/in/aminudesmond/) |


## Acknowledgments 🙏

I would like to express my gratitude to the [Azubi Africa Data Analyst Program](https://www.azubiafrica.org/data-analytics) for their support and for offering valuable projects as part of this program. Not forgeting my scrum masters on this project [Rachel Appiah-Kubi](https://www.linkedin.com/in/racheal-appiah-kubi/) & [Emmanuel Koupoh](https://github.com/eaedk)

## License 📜

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Contact 📧

For questions, feedback, and collaborations, please contact [Aminu Oluwarotimi Desmond](aminuoluwarotimi@gmail.com).
