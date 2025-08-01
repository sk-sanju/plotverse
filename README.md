# Plotverse

[![PyPI](https://img.shields.io/pypi/v/plotverse)](https://pypi.org/project/plotverse/)
[![Python](https://img.shields.io/pypi/pyversions/plotverse)](https://pypi.org/project/plotverse/)
[![GitHub tag](https://img.shields.io/github/v/tag/sk-sanju/plotverse?label=github)](https://github.com/sk-sanju/plotverse/releases)

**One library to rule them all — Pandas + Matplotlib + Seaborn.**


**Plotverse** is a unified Python library that combines:

- All functionality from `pandas`
- All `matplotlib.pyplot` functions (prefixed as `plt_`)
- All `seaborn` functions (prefixed as `sns_`)

## 📦 Installation

```bash
pip install plotverse
```
## 🧠 Usage

```bash
import plotverse as pv

df = pv.DataFrame({'x': [1, 2, 3], 'y': [4, 5, 6]})
pv.plt_plot(df['x'], df['y'])
pv.sns_heatmap(df.corr())
```

## 🎨 Themes
```bash
from plotverse.theme import dark_mode, light_mode

dark_mode()
# or
light_mode()
```

📄 LICENSE (MIT)

MIT License

Copyright (c) 2025 Sanjay S

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
