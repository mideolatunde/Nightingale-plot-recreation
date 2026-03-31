#  Nightingale Dataset Recreation

## &#128279; Project Overview
This project visualizes the causes of death among soldiers during the Crimean War from 1853-1856

## &#128279; Authors
* Ayomide Olatunde

## &#128279; Table of Contents
* [Authors](#-authors)
* [Table of Contents](#-table-of-contents)
* [Dataset Description](#-dataset-description)
* [Tools & Libraries Used](#-tools--libraries-used)
* [Workflow Implemented](#-workflow-implemented)
* [Key Insights](#-key-insights)
* [Learning Outcomes](#-learning-outcomes)
* [How to Run the project](#-how-to-run-the-project)
* [Contact](#-contact)


## &#128194; Dataset Description
**Source**: raw_night_1854_1855.xlsx, raw_night_1855_1856.xlsx
**Records**: 12 entries in each
**Columns**: 5 

#### **Columns**
- Month - the month & year the data was collected.  
- Avg Army Size - the average size of the army.  
- Disease Deaths - The number of deaths caused by diseases
- Wounds - The number of deaths caused by wounds
- Other Causes - The number of deaths caused by other causes. 


## &#128736; Tools & Libraries Used

#### **Programming Language** : `Python 3.10+` 

#### Libraries
- `pandas & janitor` – Data manipulation & cleaning

- `lets-plot` – Data Visualization

#### Environment
- `Jupyter Notebook` - Interactive analysis & documentation

- `github`


## &#129529; Workflow Implemented

The following steps were performed for this project:
1. Data Inventory  
- Checked for the missing values & duplicates.
- Checked the statistical description of the numerical columns.

2. Data Cleaning 
- Transformed the diseases, wounds and other causes to double column called 'Cause of death', 'Number'.  
- Separated the Month column into Month and Year columns.  
- Changed the 'Cause of death' column data type to categorical.  
- Created a new column 'radius' which is the square root of Number to allow for easy plotting.  

3. Data Visualization  
- Visualised the Coxcomb plot.


## 🔍 Key Insights  
- Diseases were the leading cause of death among the soldiers.  
- The number of deaths decreased the following year after florence nightingale proposed the hygiene solution.  



## &#128161; Learning Outcomes
Through this project, I demonstrated proficiency in:

#### Technical Skills
- Data cleaning.
- Data visualization (Lets-plot)
- Python programming for data science
- Jupyter Notebook documentation


#### Tools Mastered
- Python (Pandas, Janitor, Lets-plot)
- Jupyter Notebook
 

## &#128640; How to Run the Project
1. **Python Installation** (3.10 or higher)
```windows cmd
py -m python --version
```

2. **Required Libraries**
```windows cmd
py -m pip install pandas janitor lets-plot
```

#### Step-by-Step Instructions

1. **Clone/Download Repository**
- Download the project folder
- Ensure all files are in the same directory

2. **Launch Jupyter Notebook**
```windows cmd
py -m jupyter lab
```

3. **Open the Notebook**
- Open `raw_night_1854_1855.xlsx & raw_night_1855_1856.xlsx` In Jupyter.

4. **Run all cells at once or Run cells individually**

#### Troubleshooting

**Issue**: "File not found" error
**Solution**: Ensure `raw_night_1854_1855.xlsx & raw_night_1855_1856.xlsx` is in the same directory as the notebook or copy the file path with the `/`

**Issue**: Import errors
**Solution**: Install missing libraries using `py -m pip install [library-name]`


## &#128222; Contact
- **Email**: ayomideeli2002@gmail.com
- **LinkedIn**: https://linkedin.com/in/ayomide-olatunde-2859141a8
- **GitHub**: https://github.com/mideolatunde

- **Institution**: She Code Africa
- **Course**: She Code Africa Academy Program (Data Science Track)
- **Facilitator**: Ifeoma Egbogah



