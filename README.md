<div align="center">

```
██████╗ ██╗      ██████╗ ████████╗██╗     ██╗   ██╗
██╔══██╗██║     ██╔═══██╗╚══██╔══╝██║     ╚██╗ ██╔╝
██████╔╝██║     ██║   ██║   ██║   ██║      ╚████╔╝ 
██╔═══╝ ██║     ██║   ██║   ██║   ██║       ╚██╔╝  
██║     ███████╗╚██████╔╝   ██║   ███████╗   ██║   
╚═╝     ╚══════╝ ╚═════╝    ╚═╝   ╚══════╝   ╚═╝   
```

### 📊 Plotly Complete Guide — Graph Objects & Express

> A complete hands-on Plotly repository covering all major chart types using both **Plotly Express** and **Plotly Graph Objects** — from basic charts to 3D, subplots, maps & hierarchical visualizations.

<br/>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

</div>

---

## 📌 About

This is my **complete Plotly learning journal** — covering all major chart types using both `plotly.express` (high-level) and `plotly.graph_objects` (low-level), with real-world datasets and fully interactive visualizations.

All charts are **interactive** — hover, zoom, pan, and click directly in Jupyter or any browser.

---

## 📚 What's Inside

### `01-plotly_express.ipynb` — Plotly Express

High-level, DataFrame-native charting with `plotly.express`. Covers all essential chart types including line, scatter, bar, histogram, pie, donut, box, violin, area, sunburst, treemap, funnel, choropleth maps, 3D scatter & line, animations, and more.

> 📒 All important charts with full customization are documented inside the notebook.

---

### `02-plotly_graph_objects.ipynb` — Graph Objects

Low-level trace & layout control with `plotly.graph_objects`. Covers scatter, bar, pie, heatmap, box, violin, surface, 3D scatter, candlestick, waterfall, funnel, subplots with `make_subplots`, secondary Y-axis, mixed chart types, custom layouts, annotations, and more.

> 📒 All important charts with full customization are documented inside the notebook.

---

## 🔑 px vs go — When to Use Which

| | `plotly.express` | `plotly.graph_objects` |
|--|-----------------|----------------------|
| **Speed** | Fast, one-liner charts | Verbose but full control |
| **Input** | DataFrames (pandas-native) | Arrays, dicts, traces |
| **Customization** | Limited | Unlimited |
| **Best For** | EDA, quick visualization | Dashboards, complex layouts |
| **Subplots** | Limited support | Full via `make_subplots` |
| **Mixing Traces** | Not directly | Yes — `fig.add_trace()` |

> 💡 Start with `px` for speed, switch to `go` when you need precise control or mixed chart types.

---

## ⚙️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/amit-0333/plotly-go-and-express.git

# 2. Navigate into the folder
cd plotly-go-and-express

# 3. Install dependencies
pip install plotly pandas numpy jupyter

# 4. Launch Jupyter Notebook
jupyter notebook
```

---

## 🛠️ Tech Stack

- 🐍 **Python** — Core programming language
- 📊 **Plotly Express** — High-level, DataFrame-native charting
- 📐 **Plotly Graph Objects** — Low-level trace & layout control
- 🐼 **Pandas** — Data loading and manipulation
- 🔢 **NumPy** — Array generation for 3D and surface plots
- 📓 **Jupyter / Google Colab** — Interactive notebook environment

---

## 🙏 Credits & Acknowledgement

> This repository is built while learning from **[Campus X](https://www.youtube.com/@campusx-official)** — an amazing free Data Science education channel.
> Notebooks are based on class materials from Campus X. All credit for the curriculum and teaching goes to them.
> I've added my own notes, practice, and experiments on top of the class content.

---

## 👨‍💻 Author

**Amit Kumar**

[![GitHub](https://img.shields.io/badge/GitHub-amit--0333-181717?style=flat&logo=github)](https://github.com/amit-0333)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Amit%20Kumar-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/amit-kumar-a62a3640a/)
[![Kaggle](https://img.shields.io/badge/Kaggle-amitkumar038975-20BEFF?style=flat&logo=kaggle)](https://www.kaggle.com/amitkumar038975)

---

<div align="center">

> 📝 *This repository is continuously updated as I learn new visualization techniques.*

⭐ **Star this repo if it helped you learn Plotly!**

</div>
