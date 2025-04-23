# Video Game Market Analysis: GameCo

*This project was completed as part of the [CareerFoundry Data Analytics Program](https://careerfoundry.com/en/courses/become-a-data-analyst/).*


## Tools Used 

- **Excel** - Data Profiling | Cleaning | Analysis
- **KeyNote** - Presentation

## Skills Demonstrated

- Data Exploration | Description | Profiling | Quality & Integrity Assessment | Cleaning
- Descriptive Statistics | Trend Analysis
- Deriving Insights | Data Visualisation | Storytelling


## Project Overview

### Background
GameCo’s board is preparing the 2017 marketing budget and assumes that regional video game sales trends and market shares remained consistent over time. This analysis test that assumption.

### Key Questions
- Are certain types of games more popular than others?
- What publishers dominate specific markets or regions?
- Have any games or genres increased or decreased in popularity over time?
- Have regional sales trends shifted, or do they remain consistent?


## Data

- **Source**: The original dataset was sourced from **VGChartz**, and provided by CareerFoundry as part of the Data Analytics Course, including a modified version for practicing cleaning principles. 
- **Contents**: The dataset tracks global video game sales for titles that have sold more than 100,000 by publish year and includes variables such as platform, genre, publisher, and sales by region.
- **Collection**: VGChartz uses combination of retail sampling and estimation methods to represent broader sales volumes that include digital sales. The methodology changed in 2018, discontinuing estimation and instead reporting only official figures released by publishers. 
- **Limitations & Biases**: Sales figures may not represent the full population. Estimating could misrepresent digital sales and skew total sales figures. Changed methodology results in pre- and post-2018 data not being directly comparable.
- **Cleaning Notes**: Records containing missing values affecting 2,8% of the dataset were removed. Recalculated missing values in Other_Sales variable as the difference between global and other regional sales values. Other cleaning steps were minor.

🔗 [VGChartz Methodology](http://www.vgchartz.com/methodology.php)  
🔗 [Original Dataset](https://images.careerfoundry.com/public/courses/intro-to-data/E1/vgsales.xlsx)
🔗 [Modified Dataset](https://coach-courses-us.s3.amazonaws.com/public/courses/intro-to-data/E4/vgsales_dirty.xlsx)

## ⚙️ Methodology

- **Data Profiling & Exploration**: [Describe initial EDA and key metrics observed]
- **Cleaning Process**: [Steps taken to clean and prepare the data]
- **Modelling / Analysis Steps**: [Outline techniques or analytical logic used]
- **Approach**: [Reference to any frameworks used, e.g., CRISP-DM]

---

## 💡 Key Insights & Recommendations

- [Insight 1]
- [Insight 2]
- [Actionable recommendation or business implication]

---

## 📁 Deliverables
- 
- Presentation (KeyNote)
- Workbook (Excel)
---

## 🔗 Further Reading

- [Portfolio project page](https://yourportfolio.com/project-page)


---

## 📝 Takeaways

- **What I Learned**: [Discuss new skills or knowledge gained during the project.]
- **Challenges Faced**: [Describe any obstacles encountered and how you addressed them.]
- **Areas for Improvement**: [Reflect on aspects that could be enhanced in future projects.]
- **Next Steps**: [Outline potential future work or questions that arose from this project.]

---

## 📄 License

This project is licensed under the MIT License.

---

## 🗂 Repository Structure

```text
├── data/                 # Cleaned datasets (text format)
├── notebooks/            # Jupyter notebooks or scripts
├── sql-queries/          # SQL scripts
├── deliverables/         # Reports, presentations, and summaries
├── visuals/              # Charts and graphics used in reporting
├── LICENSE               # Project license (MIT)
└── README.md             # Project overview
