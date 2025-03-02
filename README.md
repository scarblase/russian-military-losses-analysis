# 🇺🇦 Military Equipment Losses Analysis (2022-2025) 📊💙💛  
Welcome to an in-depth exploration of russian military equipment losses over three tumultuous years! This repository is dedicated to supporting Ukraine by uncovering critical insights into the attrition of enemy forces. Using **PySpark** for heavy-duty data processing and **Pandas**, **Matplotlib**, and **Seaborn** for stunning visualizations, this analysis provides valuable intelligence for strategists, analysts, and patriots alike. 🇺🇦✨  

## 📌 Project Overview  
This project analyzes the daily and cumulative losses of russian military equipment, from tanks to drones, during the 2022-2025 period. By harnessing the power of **PySpark**, we process a comprehensive CSV dataset (`russia_losses_equipment.csv`), while Pandas, Matplotlib, and Seaborn bring the data to life through interactive analysis in a **Jupyter Notebook** (`russian_losses_pyspark.ipynb`). The result? A clear picture of military losses with actionable insights for Ukraine’s defenders and allies. 💪🇺🇦  

## 🌟 Key Insights & Findings  
Here’s what the data reveals after crunching the numbers:

- **Explosive Growth in Losses 💥**: russian losses skyrocket in 2024-2025, with a steep upward trend signaling intensified conflict.
- **Drones Dominate the Battlefield ✈️**: UAVs lead with **26,428 losses**, dwarfing **23,533 APCs**, **20,635 field artillery**, and **10,168 tanks** by February 2025.
- **Seasonal Spikes 📈**: Daily losses show seasonal patterns and sharp peaks (e.g., drone losses hit **190, 164, and 183 units** on key days), reflecting bursts of military activity.
- **Cumulative Toll ⚙️**: Over **38,334 vehicles and fuel tanks** lost cumulatively, underscoring the massive depletion of enemy resources.

---

## 📂 Repository Structure  
📁 **russian-military-losses-analysis**  
│── 📄 **README.md**                     # You're reading it! Project overview and guide  
│── 📊 **russia_losses_equipment.csv**   # Raw dataset with daily loss records  
│── 📓 **russian_losses_pyspark.ipynb** # Full analysis in Jupyter Notebook  
│── 🖼️ **losses.png**  # Visualization of daily and cumulative losses  

## 🖼️ Main Visualization: Daily & Cumulative Equipment Losses  

### Insights from the Plot  
This dual-axis plot provides two perspectives:

📅 **Daily Losses (Top Graph)**:  
- Tracks daily losses of tanks, APCs, field artillery, and drones.  
- **Drones Steal the Show**: Peaks like **190 (Feb 2025), 164 (Jan 2025), and 183 (Dec 2024)** units lost highlight their frequent destruction.  
- **Spikes Signal Action**: Sharp rises correlate with intense combat phases.  

📏 **Cumulative Losses (Bottom Graph)**:  
- Shows the running total over time for the same categories.  
- **Staggering Totals**: By Feb 2025, drones hit **26,428**, APCs **23,533**, field artillery **20,635**, and tanks **10,168**.  
- **Acceleration in 2024-2025**: The steep climb reflects drones’ growing role and vulnerability.  

🧐 **Trend Takeaway**: Losses escalate steadily from 2022, with a dramatic surge in 2024-2025, proving that drones are a critical yet costly asset for russia.  

---

## 📋 Data Structure: russia_losses_equipment.csv  
The dataset is the backbone of this analysis. Here’s the schema, sourced from the Jupyter Notebook:

| Column Name                 | Data Type  | Description  |
|-----------------------------|------------|-------------|
| date                        | date       | Date of recorded losses (YYYY-MM-DD) |
| day                         | integer    | Sequential day count since Feb 25, 2022 |
| aircraft                    | integer    | Number of aircraft lost |
| helicopter                  | integer    | Number of helicopters lost |
| tank                        | integer    | Number of tanks lost |
| APC                         | integer    | Number of Armored Personnel Carriers lost |
| field artillery             | integer    | Number of field artillery units lost |
| MRL                         | integer    | Number of Multiple Rocket Launchers lost |
| military auto               | double     | Number of military automobiles lost (nullable, filled with 0 in analysis) |
| fuel tank                   | double     | Number of fuel tanks lost (nullable, filled with 0 in analysis) |
| drone                       | integer    | Number of drones (UAVs) lost |
| naval ship                  | integer    | Number of naval ships lost |
| anti-aircraft warfare       | integer    | Number of anti-aircraft warfare systems lost |
| special equipment           | double     | Number of special equipment units lost (nullable, filled with 0) |
| mobile SRBM system          | double     | Number of mobile Short-Range Ballistic Missile systems lost (nullable) |
| greatest losses direction   | string     | Location/direction of greatest losses (nullable) |
| vehicles and fuel tanks     | double     | Total vehicles and fuel tanks lost (nullable, filled with 0) |
| cruise missiles             | double     | Number of cruise missiles lost (nullable, filled with 0) |
| submarines                  | double     | Number of submarines lost (nullable, filled with 0) |

---

## 🚀 Strategic & Military Implications  
This analysis isn’t just numbers—it’s a **strategic tool** for Ukraine’s defense! 🇺🇦🔥  

- **Tactical Intelligence 🕵️**: Identify enemy equipment depletion trends and optimize battlefield strategy.  
- **Resource Forecasting 📦**: Predict enemy equipment shortages to aid military planning.  
- **AI-Powered Predictions 🤖**: Train models to forecast loss trends and enhance operational efficiency.  
- **Geopolitical Leverage 🌍**: Use data-driven insights to strengthen Ukraine’s diplomatic and strategic position.  

---

## ⚙️ Installation & Setup  
### Ready to analyze russian losses? Follow these steps:  

Clone the Repo 🖥️:  
```sh  
git clone https://github.com/scarblase/russian-military-losses-analysis.git  
cd russian-military-losses-analysis  
```

Install Dependencies 📚:  
```sh  
pip install pandas numpy pyspark matplotlib seaborn jupyter marimo  
```

Launch the Notebook 🚀:  
```sh  
jupyter notebook  
```

Open `russian_losses_pyspark.ipynb` and run the cells to explore the analysis!  

---

## 🛠️ Tools & Technologies  
This project is powered by:
- **Python 🐍**: The core language
- **PySpark ⚡**: Big data processing
- **Pandas 📈**: Data wrangling
- **Matplotlib & Seaborn 🎨**: Eye-catching visualizations
- **Jupyter Notebook/Marimo(_https://marimo.io_) 📓**: Interactive analysis hub

---

## 🎯 Future Improvements  
- **Predictive Modeling 🔮**: Forecast future russian losses using ML.
- **Live Data Updates ⏳**: Automate real-time tracking.
- **Geospatial Insights 🗺️**: Map loss locations for deeper analysis.

---

## 🤝 Contributing  
Got ideas? Open an issue or submit a pull request—let’s make this project even stronger! 💪🇺🇦  

📧 Contact: Reach me on LinkedIn or email me at tmhomenko@gmail.com.  

**🇺🇦 Glory to Ukraine! Слава Україні! 🇺🇦**

