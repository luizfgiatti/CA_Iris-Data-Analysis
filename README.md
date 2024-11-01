{\rtf1\ansi\ansicpg1252\cocoartf2709
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww19380\viewh14480\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # CA1 Project: Iris Data Analysis and NASA APOD Data\
\
## Overview\
\
This project contains analyses on two datasets: the **Iris dataset** and data from the **NASA Astronomy Picture of the Day (APOD) API**. These analyses are part of a Continuous Assessment (CA) for an Artificial Intelligence programming course.\
\
## Project Structure\
\
- **apod_data.csv**: Summary of NASA APOD data in CSV format.\
- **apod_data.json**: Raw NASA APOD data retrieved from the API in JSON format.\
- **iris.csv**: Original Iris dataset used for data analysis.\
- **Problem_1and2.ipynb**: Jupyter Notebook containing solutions for Problems 1 and 2, including:\
  - Fetching NASA APOD data using the API.\
  - Storing and processing APOD data.\
- **Problem_3.ipynb**: Jupyter Notebook containing solutions for Problem 3, which involves:\
  - Creating a special 2D array and performing various numerical operations with NumPy.\
- **Problem_4.ipynb**: Jupyter Notebook containing solutions for Problem 4, where:\
  - The Iris dataset is loaded, cleaned, analyzed, and visualized using pandas and seaborn.\
- **Programming_CA_2024.pdf**: The original project guidelines and instructions for the CA.\
\
## Project Tasks\
\
1. **Problem 1**: Fetch and analyze data from the NASA APOD API.\
   - Retrieve daily astronomy pictures using the NASA API.\
   - Save the retrieved data in JSON format and create a summarized CSV file.\
\
2. **Problem 3**: Numerical analysis using NumPy on a custom 2D array.\
   - Generate a special 2D array with specific properties.\
   - Calculate the mean, median, and standard deviation, and analyze the array's characteristics.\
\
3. **Problem 4**: Data analysis and visualization of the Iris dataset using pandas.\
   - Clean the Iris dataset and perform exploratory data analysis.\
   - Generate visualizations such as scatter plots and pair plots to understand relationships between features.\
\
## How to Run the Project\
\
1. **Clone the Repository**:\
   - Clone this repository to your local machine:\
\
     ```bash\
     git clone https://github.com/luizfgiatti/CA_Iris-Data-Analysis.git\
     ```\
\
2. **Install Dependencies**:\
   - Make sure you have Python and Jupyter Notebook installed. Install additional required libraries with:\
\
     ```bash\
     pip install pandas numpy seaborn matplotlib\
     ```\
\
3. **Run the Jupyter Notebooks**:\
   - Open each notebook (`Problem_1and2.ipynb`, `Problem_3.ipynb`, `Problem_4.ipynb`) in Jupyter Notebook or Jupyter Lab and run the cells to execute the analyses.\
\
4. **View Results**:\
   - Outputs and visualizations are embedded within the notebooks. Additional result files like `apod_data.csv` and plots generated within the notebooks are stored in the project directory.\
\
## Requirements\
\
- Python 3.x\
- Jupyter Notebook\
- Libraries:\
  - pandas\
  - numpy\
  - seaborn\
  - matplotlib\
\
## Additional Information\
\
This project explores foundational data analysis techniques, focusing on dataset cleaning, statistical analysis, and data visualization. The analyses are presented in Jupyter Notebooks, allowing for step-by-step demonstration of each task.\
\
---\
\
}