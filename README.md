
# ⚽ FIFA23 Wage vs Value Interactive Visualization

This project analyzes and visualizes FIFA23 player data, particularly focusing on the relationship between players' wages and their transfer values. It combines the power of **Pandas**, **Seaborn**, and **Bokeh** for both static and interactive visual exploration.

---

## 📌 Features

- Load and inspect FIFA23 dataset using `pandas`
- Clean and preprocess monetary columns ("Value", "Wage")
- Compute new column: wage minus value difference
- Visualize data using `seaborn` (static) and `bokeh` (interactive)
- Interactive plot includes zoom, pan, hover tooltips

---

## 📊 Sample Visualization

The scatter plot displays:
- **X-axis**: Player Wages (€)
- **Y-axis**: Player Market Values (€)
- Color-coded, interactive data points with player names on hover

---

## 🛠️ Setup

### 1. Clone this repository
```bash
git clone https://github.com/your-username/fifa23-wage-vs-value.git
cd fifa23-wage-vs-value
```

### 2. Install dependencies
```bash
pip install pandas numpy seaborn bokeh
```

---

## 🧪 How to Run

Ensure your `fifa23.csv` file is in the same directory. Then, simply run the Python script:
```bash
python analysis.py
```

The script will:
- Load and process the dataset
- Display a static scatterplot using Seaborn
- Launch an interactive Bokeh scatterplot in your browser

---

## 📁 File Structure

```
├── FifaProject.ipynb          # main script with visualization
├── fifa23.csv           # input dataset
└── README.md            # this file
```

---

## 📚 Dependencies

- numpy
- pandas
- seaborn
- bokeh

Install all with:
```bash
pip install -r requirements.txt
```

---

## 📃 License

This project is open source and free to use under the MIT License.
