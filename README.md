# Alaska Aviation Facilities Analysis with Python

## 📌 Project Overview

This project explores aviation facility data for Alaska using Python and Pandas. The analysis works with an Excel-based dataset containing information about airports, seaplane bases, and heliports.

The project demonstrates a beginner-level data analysis workflow, including spreadsheet data loading, exploratory analysis, filtering, sorting, aggregation, descriptive statistics, data visualization, and exporting analysis results.

The project was developed as part of IBM's **Analyzing Spreadsheet Data with Python** learning experience and further organized and presented as a portfolio project.

---

## 🎯 Project Objectives

The analysis focuses on answering the following questions:

1. What types of aviation facilities exist in Alaska?
2. Which facilities are classified as seaplane bases?
3. What are the five highest aviation facilities based on elevation?
4. What is the average elevation of aviation facilities?
5. What are the highest and lowest elevation values?
6. What patterns can be observed through basic data visualizations?

---

## 📊 Dataset

The project uses an Excel workbook containing aviation facility information.

### Workbook sheets

* `Facilities`
* `Runway`
* `Schedules`
* `Remarks`

The primary analysis in this project focuses on the **Facilities** sheet.

### Dataset size

* **751 aviation facilities**
* **103 columns**
* **561 Airports**
* **138 Seaplane Bases**
* **52 Heliports**

The dataset includes attributes describing aviation facilities, including facility type, location identifiers, and airport reference point elevation.

---

## 🛠️ Tools & Technologies

### Programming & Analysis

* Python
* Pandas

### Visualization

* Matplotlib

### Data Source / File Handling

* Microsoft Excel
* OpenPyXL

### Development Environment

* Jupyter Notebook

### Version Control

* Git
* GitHub

---

## 🔎 Analysis Performed

### 1. Aviation Facility Types

The project identifies the different types of aviation facilities represented in the dataset and calculates their distribution.

The dataset contains:

| Facility Type |   Count |
| ------------- | ------: |
| Airport       |     561 |
| Seaplane Base |     138 |
| Heliport      |      52 |
| **Total**     | **751** |

This analysis provides an overview of the composition of Alaska's aviation facilities represented in the dataset.

---

### 2. Seaplane Base Analysis

The project filters the dataset to identify all facilities classified as:

`SEAPLANE BASE`

The resulting records are also exported to a separate Excel file for further use.

Output:

`output/seaplane.xlsx`

---

### 3. Top 5 Facilities by Elevation

Facilities are sorted according to the `ARPElevation` column to identify the five highest facilities in the dataset.

The five highest records are:

| Location ID | Facility Type | Elevation |
| ----------- | ------------- | --------: |
| `'AA09`     | Airport       |     3,984 |
| `'93AK`     | Airport       |     3,720 |
| `'4Z5`      | Airport       |     3,620 |
| `'2AK7`     | Airport       |     3,600 |
| `'AK80`     | Airport       |     3,530 |

---

### 4. Elevation Statistics

The project calculates basic descriptive statistics for aviation facility elevation.

* **Average elevation:** 425.93
* **Minimum elevation:** 0
* **Maximum elevation:** 3,984

These statistics provide a basic overview of the elevation range represented in the dataset.

---

## 📈 Data Visualizations

Three visualizations were added to provide a clearer exploratory view of the dataset.

### Facility Type Distribution

A bar chart showing the number of Airports, Seaplane Bases, and Heliports.

<img width="786" height="489" alt="Distribution of Aviation Facility Types" src="https://github.com/user-attachments/assets/46c8ade1-71f3-445a-be9a-5ba265b14246" />


---

### Top 5 Facilities by Elevation

A horizontal bar chart comparing the five highest aviation facilities based on `ARPElevation`.

<img width="886" height="485" alt="Top 5 Aviation Facilities by Elevation" src="https://github.com/user-attachments/assets/507a6e45-8b24-4d1f-93ff-ffee6842a260" />


---

### Elevation Distribution

A histogram showing the distribution of aviation facility elevations across the dataset.

<img width="888" height="489" alt="Distribution of Aviation Facility Elevations" src="https://github.com/user-attachments/assets/83b36cd2-bdfe-45a2-873b-6482fb79b75f" />


---

## 💡 Key Findings

The analysis produced several observations:

* Airports represent the largest facility category in the dataset, with **561 facilities**.
* The dataset contains **138 seaplane bases** and **52 heliports**.
* The average facility elevation is approximately **425.93**.
* Facility elevations range from **0 to 3,984**.
* The five highest facilities identified by `ARPElevation` are all classified as airports.
* Visualizations provide an additional perspective on facility composition and elevation distribution.

---

## 📁 Project Structure

```text
alaska-aviation-facilities-analysis/
│
├── README.md
├── requirements.txt
│
├── data/
│   └── Airport_Data.xlsx
│
├── notebooks/
│   └── Analyzing_Spreadsheet_Data_with_Python.ipynb
```

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/alaska-aviation-facilities-analysis.git
```

### 2. Navigate to the project directory

```bash
cd alaska-aviation-facilities-analysis
```

### 3. Install the required libraries

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the notebook

Navigate to:

```text
notebooks/Analyzing_Spreadsheet_Data_with_Python.ipynb
```

---

## 🧠 Skills Demonstrated

### Python

* Python programming fundamentals
* Pandas
* DataFrame operations
* Excel data loading
* Data filtering
* Sorting
* Aggregation
* Descriptive statistics
* Data export

### Data Analysis

* Exploratory data analysis
* Categorical analysis
* Filtering and segmentation
* Ranking
* Summary statistics
* Basic data visualization
* Analytical interpretation

### Tools

* Jupyter Notebook
* Microsoft Excel
* Git
* GitHub

---

## 🔮 Future Improvements

This project provides a foundation for deeper analysis of the available aviation dataset.

Potential improvements include:

* Analyze runway characteristics using the `Runway` sheet
* Explore information from the `Schedules` sheet
* Investigate relationships between facility type and elevation
* Analyze the geographic distribution of aviation facilities
* Perform additional data-quality checks
* Create more advanced visualizations
* Develop an interactive dashboard using Power BI
* Combine multiple sheets to create a more comprehensive aviation analysis

---

## 📚 Learning Context

This project was developed as part of IBM's **Analyzing Spreadsheet Data with Python** learning experience.

The portfolio version extends the original exercise by organizing the analysis into a structured project and adding data visualizations, key findings, documentation, and a reproducible GitHub structure.

---

## 👤 Author

**Muhammad**

Aspiring Data Analyst | Business Data Analytics Student

Interested in Python, SQL, Data Analysis, Business Intelligence, and Data Visualization.

---

⭐ If you found this project useful, feel free to explore the notebook and analysis.
