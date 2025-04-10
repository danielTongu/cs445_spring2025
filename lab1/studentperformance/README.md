# Student Performance Data Visualization

This project visualizes the **Student Performance dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Student+Performance).  
We analyze and plot trends from the `student-mat.csv` file which includes student grades and background details.

## 🎯 Objective

The goal is to reinforce data analysis and visualization skills using real-world education data.  
We use Matplotlib to generate and explain different types of charts.

## 📁 Dataset Details

- **File used**: student-mat.csv
- **Description**: Contains student background information and academic performance in math.
- **Attributes**: Study time, parental education, grades (G1, G2, G3), failures, absences, and more.

## ▶️ How to Run

1. Make sure you have Python installed.
2. Install required packages:
   ```bash
   pip install matplotlib pandas
   ```
3. Download `student-mat.csv` from the UCI site and place it in the same folder.
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook StudentPerformance_Visualization.ipynb
   ```
5. Run all cells to generate the graphs and explanations.

## 📈 Visualizations

This notebook includes the following charts:

| Chart Type   | Description |
|--------------|-------------|
| **Bar Chart** | Number of students per final grade group |
| **Line Graph** | Average grade vs. weekly study time |
| **Pie Chart** | Distribution of father's education levels |
| **Box Plot** | Spread of final grade (G3) scores |

Each visualization is saved in image format using: `DanielTongu_<Title>.png`

## 🗂 Project Files

```
├── StudentPerformance_Visualization.ipynb
├── student-mat.csv
├── DanielTongu_StudentGradeBarChart.png
├── DanielTongu_StudyTimeLineGraph.png
├── DanielTongu_ParentalEducationPieChart.png
├── DanielTongu_FinalGradeBoxPlot.png
└── README.md
```

## 👤 Author

Daniel Tongu

## 📜 License

For academic and learning purposes only.
