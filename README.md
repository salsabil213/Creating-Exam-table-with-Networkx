# 🎓 Creating Exam Table with NetworkX 📊

This project utilizes the **NetworkX** library to create and manage exam schedules. The data for this project has been sourced from **Buraydah Private College**, a Saudi Arabian college. This repository demonstrates how graph-based algorithms can be applied to optimize exam scheduling.

## 📋 Table of Contents
- [📖 Introduction](#-introduction)
- [✨ Features](#-features)
- [🛠️ Technologies Used](#️-technologies-used)
- [🚀 Setup and Usage](#-setup-and-usage)
- [📂 Data Source](#-data-source)
- [📜 License](#-license)

## 📖 Introduction
Efficient exam scheduling is a critical task for educational institutions. This project leverages the power of NetworkX to:
- Represent exams and their constraints as a graph.
- Use graph algorithms to ensure conflict-free exam scheduling.
- Optimize scheduling based on various constraints.

The dataset used in this project comes from **Buraydah Private College**, located in Saudi Arabia.

### 🧠 Algorithm
The scheduling process is implemented using the **Greedy Coloring Algorithm** with the **Smallest Last** strategy. This approach:
- Orders nodes (exams) by the smallest degree last.
- Minimizes conflicts while assigning colors (time slots) to nodes.

This ensures an efficient and conflict-free exam timetable.

## ✨ Features
- 📈 Graph-based representation of exams and conflicts.
- ✅ Conflict-free scheduling using graph coloring techniques.
- 🔍 Visualization of schedules and conflicts for better insights.

## 🛠️ Technologies Used
- 🧮 **NetworkX** for graph representation and algorithms.
- 📒 **Jupyter Notebook** for interactive development and analysis.
- 🐍 Python libraries for data processing and visualization.

## 🚀 Setup and Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/salsabil213/Creating-Exam-table-with-Networkx.git
   cd Creating-Exam-table-with-Networkx
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Run the notebook and follow the instructions to input your data and generate exam schedules.

## 📂 Data Source
The dataset used in this project is sourced from **Buraydah Private College** in Saudi Arabia. The data includes exam details, constraints, and other relevant information.
---

Feel free to contribute to this repository or suggest improvements! 😊
