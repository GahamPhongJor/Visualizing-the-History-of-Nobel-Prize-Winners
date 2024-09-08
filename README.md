# Visualizing-the-History-of-Nobel-Prize-Winners
This is a project from the Associate Data Scientist With Python from Datacamp
Visualizing the History of Nobel Prize Winners


# Project Description

The Nobel Prize has been among the most prestigious international awards since 1901. Each year, awards are bestowed in chemistry, literature, physics, physiology or medicine, economics, and peace. In addition to the honor, prestige, and substantial prize money, the recipient also gets a gold medal with an image of Alfred Nobel (1833 - 1896), who established the prize.

The Nobel Foundation has made a dataset available of all prize winners from the outset of the awards from 1901 to 2023. The dataset used in this project is from the Nobel Prize API and is available in the nobel.csv file in the data folder.
In this project, you'll get a chance to explore and answer several questions related to this prizewinning data. And we encourage you then to explore further questions that you're interested in!

The Nobel Prize is awarded yearly to scientists and scholars in chemistry, literature, physics, medicine, economics, and peace, with the first prize awarded in 1901. Are there any biases in the way the honors are awarded? Use your data manipulation and visualization skills to explore the history of this coveted prize.

# Dataset
nobel.csv

# Dataset Overview
The dataset used for this analysis contains information about Nobel Prize laureates and includes various attributes such as:
	• Name and surname of the laureate
	• Birth and death dates
	• Birth and death places (countries)
	• Nobel Prize category and year
	• Summary of the laureate's contribution
	• Gender and organization (if applicable)
	
The dataset spans from 1900 to 2020 and provides a comprehensive collection of Nobel Prize laureate information for in-depth analysis.

# Project Structure
The project follows a structured organization:
	• data/: Contain the dataset file
	• notebooks/: Jupyter notebooks for data cleaning, exploration, visialization and analysis
	• README.md: Documentation about the project (you are here)


# Visualization & Data Analysis
	• Visualization: Line plots in seaborn
	• Data Manipulation: Subsetting, Grouping , Counting Value
	
	
# Programming Language
	• Python
	
# Tasks and Questions To Perform
Analyze Nobel Prize winner data and identify patterns by answering the following questions:
  1.  What is the most commonly awarded gender and birth country?
	  -  Store your answers as string variables top_gender and top_country.
  2.  Which decade had the highest ratio of US-born Nobel Prize winners to total winners in all categories?
	  -  Store this as an integer called max_decade_usa.
  3.  Which decade and Nobel Prize category combination had the highest proportion of female laureates?
	  -  Store this as a dictionary called max_female_dict where the decade is the key and the category is the value. There should only be one key:value pair.
  4.  Who was the first woman to receive a Nobel Prize, and in what category?
	  -  Save your string answers as first_woman_name and first_woman_category.
  5.  Which individuals or organizations have won more than one Nobel Prize throughout the years?
	  -  Store the full names in a list named repeat_list.

