# Plotverse

[![PyPI](https://img.shields.io/pypi/v/plotverse)](https://pypi.org/project/plotverse/)
[![Python](https://img.shields.io/pypi/pyversions/plotverse)](https://pypi.org/project/plotverse/)
[![GitHub tag](https://img.shields.io/github/v/tag/sk-sanju/plotverse?label=github)](https://github.com/sk-sanju/plotverse/releases)

> **One library to rule them all — Pandas + Matplotlib + Seaborn**

---

## 🚀 Overview

**Plotverse** is a unified Python library that combines the power of:

- 🐼 **Pandas** — full data manipulation capabilities  
- 📊 **Matplotlib** — all `pyplot` functions available as `plt_`  
- 🎨 **Seaborn** — all visualization functions available as `sns_`  

It provides a single, consistent interface for data analysis and visualization.

---

## 📦 Installation

```bash
pip install plotverse
```
🧠 Usage
```
Python
import plotverse as pv

df = pv.DataFrame({
    'x': [1, 2, 3],
    'y': [4, 5, 6]
})

pv.plt_plot(df['x'], df['y'])
pv.sns_heatmap(df.corr())
```
🎨 Themes
```
Python
from plotverse.theme import dark_mode, light_mode

dark_mode()
# switch back
light_mode()
```
⚡ Features
🔗 Unified API combining Pandas + Matplotlib + Seaborn
📊 Access matplotlib functions using plt_ prefix
🎨 Access seaborn functions using sns_ prefix
🧠 Simplified workflow for data analysis
🚀 Faster and cleaner visualization pipeline
📄 License
This project is licensed under the MIT License.
