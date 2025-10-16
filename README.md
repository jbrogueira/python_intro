# Introduction to Python

<img src="NOVASBE-LOGO.png" alt="Nova SBE Logo" width="180">

Welcome to the **Introduction to Python** repository!  
This collection of Jupyter notebooks is designed to help beginners get started with Python programming through practical, hands-on examples.  

Each notebook focuses on a different aspect of the Python ecosystem — from language fundamentals to working with data and visualization.
 
---

### Author

**[João Brogueira de Sousa](https://jbsousa.com/)**  
Assistant Professor in Economics, Nova SBE  

If you have questions, suggestions, or find an issue, feel free to reach out or open an [issue](../../issues) on GitHub.

---

## Contents

This repository includes the following notebooks:

0. **Getting Started: What is Python, Setup & Git/GitHub**  
   How it’s used, how scripts and notebooks differ, and how Python executes code. Installing Python/Miniconda, setting up Jupyter, running scripts and notebooks, basic command-line workflow, Git fundamentals (clone, commit, push), and using GitHub to share work.

1. **Python Essentials**  
   *Assignment statements, data types, and operators*  
   Learn how to declare variables, work with different data types (strings, numbers, booleans, etc.), and use basic operators to manipulate data.

2. **Methods and Functions, Modules, Conditionals, and Loops**  
   Explore how to organize your code into reusable functions, use built-in and custom modules, and control program flow with conditionals and loops.

3. **Working with Data: Pandas, Aggregations, and Transforms**  
   Get familiar with the `pandas` library to load, manipulate, and analyze datasets.  
   Learn how to use aggregations, transforms, and apply operations efficiently.

4. **Plotting with Matplotlib**  
   Discover how to create and customize plots using the `matplotlib` library — from basic line charts to more advanced visualizations.

5. **Scraping Data with Python**  
   Learn how to collect data from websites and datasets. 

---

## How to Use

You can explore the notebooks in two ways:

### Option 1 — Run Online (No Installation)
You can open and run the notebooks directly in your browser using one of these platforms:

- [Google Colab](https://colab.research.google.com/)
- [Binder](https://mybinder.org/)

 [**Open in Binder**](https://mybinder.org/v2/gh/YOUR_USERNAME/YOUR_REPO/main)

*(Replace `YOUR_USERNAME` and `YOUR_REPO` with your GitHub details.)*

### Option 2 — Run Locally (with Conda)

1. **Clone this repository**
   ```bash
   git clone https://github.com/jbrogueira/python_intro.git
   cd python_intro
   ```

2. **Install Conda (if you don’t have it already)**  
   You can install Conda by downloading one of the following distributions:

   - [**Anaconda**](https://www.anaconda.com/products/distribution) — includes many data science packages by default.  
   - [**Miniconda**](https://docs.conda.io/en/latest/miniconda.html) — a lightweight alternative that lets you install only what you need.

   After installation, make sure Conda is available by running:
   ```bash
   conda --version
   ```

3. **Create and activate the conda environment**
   ```bash
   conda env create -f environment.yml
   conda activate intro-python
   ```

4. **Start Jupyter**
   ```bash
   jupyter notebook
   ```

---

## Learning Goals

By the end of these notebooks, you will be able to:

- Understand Python syntax and basic programming constructs  
- Write and organize your own functions and modules  
- Analyze and transform data using `pandas`  
- Visualize data using `matplotlib`  
- Retrieve and process data from the web  

---

##  Recommended Resources

- [Python Official Documentation](https://docs.python.org/3/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [QuantEcon Python Lectures](https://python.quantecon.org/)

---

## About

These notebooks were prepared for students at **Nova SBE** as part of an introductory series on Python programming for economics.  
They are intended as a practical companion for self-learning and classroom use.

---

## License

This project is licensed under the [MIT License](LICENSE).
