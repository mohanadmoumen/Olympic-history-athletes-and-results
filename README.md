# Olympic Games Data Analysis

## Project Overview

This project analyzes historical Olympic Games data to uncover insights about athlete performance, medal distributions, and trends across different countries, sports, and time periods. The analysis aims to provide a comprehensive understanding of Olympic history through data exploration and visualization.

## Dataset

### 1. Athlete Events Dataset (`athlete_events.csv`)
**Size**: ~271,118 records  
**Time Period**: 1896-2016  
**Columns**:
- `ID`: Unique athlete identifier
- `Name`: Athlete's full name
- `Sex`: Gender (M/F)
- `Age`: Athlete's age at time of competition
- `Height`: Height in centimeters
- `Weight`: Weight in kilograms
- `Team`: Country/team name
- `NOC`: National Olympic Committee code (3-letter)
- `Games`: Olympic Games edition (e.g., "1992 Summer")
- `Year`: Year of the games
- `Season`: Summer or Winter
- `City`: Host city
- `Sport`: Sport category
- `Event`: Specific event name
- `Medal`: Medal won (Gold/Silver/Bronze/NA)

### 2. NOC Regions Dataset (`noc_regions.csv`)
**Size**: ~231 records  
**Purpose**: Maps NOC codes to country names and regions  
**Columns**:
- `NOC`: 3-letter country code
- `region`: Full country/region name
- `notes`: Additional information (historical names, etc.)

---

## Project Goals

The main objectives of this analysis are:

* **Data Cleaning:** Load the dataset and handle missing values, particularly in the 'Medal' column, to ensure accurate analysis.
* **Top Countries:** Identify the Top 5 medal-winning countries.
* **Top Sports:** Determine the Top 5 sports based on the number of medals awarded.
* **Gender Distribution:** Analyze the distribution of medals between male and female athletes.
* [cite_start]**Performance Over Time:** Track the total number of medals awarded per to observe historical trends.
* [cite_start]**Seasonal Comparison:** Compare the total medal counts between the Summer and Winter Olympics.

---

## Tools Used
* **Python**
* **Jupyter Notebook**
* **Pandas:** For data loading, cleaning, and aggregation.
* **NumPy:** For numerical operations.
* **Matplotlib:** For data visualization.

---

## How to Run   

1.  Ensure you have Python, Jupyter Notebook, and the required libraries (`pandas`, `numpy`, `matplotlib`) installed.
2.  Place the `athlete_events.csv` file inside a `data/` directory in the root of the project.
3.  Open and run the `main.ipynb` notebook to see the full analysis.

---

## Key Findings

*(results and visualizations.)*

### 1. Top Medal-Winning Countries

`[bar chart showing the top 5 countries by total medals]`

* **Finding:** shows that the top 5 medal-winning countries are... (fill in your findings).

### 2. Top Sports by Medal Count

`[Insert bar chart showing the top 5 sports by total medals]`

* **Finding:** The sports that have awarded the most medals throughout history are... (fill in your findings).

### 3. Medal Distribution by Gender

`[Insert your pie chart or bar chart of medals won by male vs female athletes]`

* **Finding:** The data shows that... (e.g., "male athletes have historically won significantly more medals, though trends may show this gap closing in recent decades.")

### 4. Medal Trends Over Time

`[PLACEHOLDER: Insert your line graph showing the total number of medals awarded per decade]`

* **Finding:** As seen in the chart, the number of medals awarded has... (e.g., "steadily increased over the decades, reflecting the growth of the Olympic Games.")

### 5. Summer vs. Winter Games

`[Insert your bar chart comparing total medals for Summer vs Winter seasons]`

* **Finding:** The Summer Olympics account for a significantly larger portion of the total medals awarded compared to the Winter Olympics.