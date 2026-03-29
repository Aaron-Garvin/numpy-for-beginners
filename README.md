<div align="center">

<!-- HEADER BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:16213e&height=200&section=header&text=NumPy%20for%20Beginners&fontSize=50&fontColor=58a6ff&fontAlignY=38&desc=Your%20hands-on%20guide%20to%20numerical%20computing%20in%20Python&descColor=8b949e&descAlignY=60&animation=fadeIn" width="100%"/>

<!-- BADGES ROW 1 -->
<p>
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-1.x-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google%20Colab-Ready-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white"/>
  <img src="https://img.shields.io/badge/Level-Beginner%20Friendly-22c55e?style=for-the-badge"/>
</p>

<!-- BADGES ROW 2 -->
<p>
  <img src="https://img.shields.io/github/stars/Aaron-Garvin/numpy-for-beginners?style=social"/>
  <img src="https://img.shields.io/github/forks/Aaron-Garvin/numpy-for-beginners?style=social"/>
  <img src="https://visitor-badge.laobi.icu/badge?page_id=Aaron-Garvin.numpy-for-beginners"/>
</p>

<!-- OPEN IN COLAB BUTTON -->
<a href="YOUR_COLAB_NOTEBOOK_LINK_HERE">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" height="35"/>
</a>

<br/><br/>

> 🎯 **A beginner-friendly NumPy notebook** — from zero to arrays, slicing, broadcasting & more.
> No prior NumPy experience needed. Just curiosity! 🚀

</div>

---

## 🌟 Why This Notebook?

If you're stepping into **Data Science** or just want to level up your Python — **NumPy is your first stop**.

This notebook is built to make that journey **easy, visual, and practical** — every concept is explained in plain language with working code examples you can run instantly in Google Colab.

---

## 📚 What's Inside — 8 Chapters

| # | Chapter | What You'll Learn |
|---|---------|------------------|
| 1️⃣ | **Introduction to NumPy** | What is NumPy, why it's faster than Python lists |
| 2️⃣ | **Multidimensional Arrays** | 1D, 2D, 3D arrays, `.ndim`, `.shape` attributes |
| 3️⃣ | **Slicing** | Row selection, column selection, range slicing |
| 4️⃣ | **Arithmetic Operations** | Scalar math, vectorized functions, element-wise ops |
| 5️⃣ | **Broadcasting** | Operate on arrays of different shapes |
| 6️⃣ | **Aggregate Functions** | `sum`, `min`, `max`, `mean` with axis control |
| 7️⃣ | **Filtering** | Boolean filtering, `np.where()` |
| 8️⃣ | **Random Number Generation** | Seeds, uniform distribution, shuffle, random choice |

---

## 🚀 Getting Started

### ▶️ Run in Google Colab (Recommended — No Setup!)

Click the button below and start learning instantly in your browser:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_COLAB_NOTEBOOK_LINK_HERE)

### 💻 Run Locally

```bash
# 1. Clone this repo
git clone https://github.com/Aaron-Garvin/numpy-for-beginners.git

# 2. Install NumPy
pip install numpy

# 3. Open the notebook
jupyter notebook Practice_py_Numpy.ipynb
```

---

## 📸 Sneak Peek

```python
import numpy as np

# Why NumPy beats Python lists
my_list  = [1, 2, 3, 4]
my_array = np.array([1, 2, 3, 4])

print(my_list * 2)    # [1, 2, 3, 4, 1, 2, 3, 4]  ← just repeats!
print(my_array * 2)   # [2, 4, 6, 8]               ← actual math! ✅

# Broadcasting — multiplication table in one line!
nums = np.array([[1],[2],[3],[4],[5],[6],[7],[8],[9],[10]])
mult = np.array([1, 2, 3, 4, 5, 6, 7, 8, 9, 10])
print(nums * mult)    # Full 10x10 multiplication table 🔥

# Filtering with np.where()
ages = np.array([21, 17, 19, 20, 16, 18, 34])
teenagers = np.where((ages >= 13) & (ages <= 19))
print(ages[teenagers])   # [17, 19, 16, 18] ✅
```

---

## 🗺️ Learning Path

```
🐍 Know Basic Python?
        │
        ▼
📘 Chapter 1 — Understand what NumPy is & why it matters
        │
        ▼
🔢 Chapter 2 — Create and inspect arrays (1D → 3D)
        │
        ▼
✂️  Chapter 3 — Slice rows, columns, and ranges
        │
        ▼
➕ Chapter 4 — Math on arrays (scalar, vectorized, element-wise)
        │
        ▼
📡 Chapter 5 — Broadcasting (different shapes, no problem!)
        │
        ▼
📊 Chapter 6 — Aggregate data with sum, mean, min, max
        │
        ▼
🔍 Chapter 7 — Filter arrays with conditions & np.where()
        │
        ▼
🎲 Chapter 8 — Generate random numbers, shuffle, seed
        │
        ▼
🎉 You're NumPy-ready for Data Science!
```

---

## 🛠️ Requirements

```
Python  >= 3.x
NumPy   >= 1.x
```

Or just use **Google Colab** — everything is pre-installed! ☁️

---

## 🙋‍♂️ Who Is This For?

- 🎓 Students starting out with Python & Data Science
- 💡 Developers curious about numerical computing
- 📊 Anyone who wants to understand how NumPy arrays actually work
- 🧠 Learners who want clean, well-explained code examples

---

## 🤝 Contributing

Found a typo? Have a better example? Contributions are welcome!

1. Fork this repo
2. Create your branch: `git checkout -b improve/chapter-3`
3. Commit your changes: `git commit -m "Improve slicing examples"`
4. Push & open a Pull Request ✅

---

## ⭐ Show Some Love

If this notebook helped you, please consider giving it a **star** ⭐ — it helps others discover it too!

<div align="center">
  <a href="https://github.com/Aaron-Garvin/numpy-for-beginners/stargazers">
    <img src="https://img.shields.io/github/stars/Aaron-Garvin/numpy-for-beginners?style=for-the-badge&color=yellow"/>
  </a>
</div>

---

## 📬 Connect With Me

<div align="center">

  <a href="https://www.linkedin.com/in/aaron-garvin">
    <img src="https://img.shields.io/badge/LinkedIn-Aaron%20Garvin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://github.com/Aaron-Garvin">
    <img src="https://img.shields.io/badge/GitHub-Aaron--Garvin-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  &nbsp;
  <a href="mailto:garvinaaron26@gmail.com">
    <img src="https://img.shields.io/badge/Email-garvinaaron26@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0d1117&height=100&section=footer" width="100%"/>

**Made with ❤️ by [Aaron Garvin](https://github.com/Aaron-Garvin)**

*If this helped you — star it, share it, pass it on* 🚀

</div>
