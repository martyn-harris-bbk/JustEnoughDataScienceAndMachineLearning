
# Just Enough Data Science and Machine Learning

Authors: **Mark Levene** and **Martyn Harris**

This repository accompanies the book *Just Enough Data Science and Machine Learning*, which offers a comprehensive and accessible introduction to data science. By focusing on core statistical concepts, exploratory data analysis, hypothesis testing, and algorithmic methods, it helps readers build a solid intuition for how data science and machine learning methods discover patterns and insights from real-world data.

---

## Book Overview

- **Minimal Math & Code**  
  The core methods are explained without heavy reliance on advanced mathematics or elaborate code, making the book accessible to a broad audience.

- **Fundamental Statistical Concepts**  
  Readers will learn the basics of probability, distributions, and hypothesis testing—essential building blocks for data science.

- **Data Exploration & Visualization**  
  Learn how to use visual tools and techniques to explore and understand datasets before any modeling takes place.

- **Practical Machine Learning**  
  Machine learning is presented as the algorithmic component of data science, illustrating how patterns are discovered from input data.

- **Real-World Case Studies**  
  Each concept is reinforced with practical examples and real-world data to help solidify understanding.

- **Timeless Python Examples**  
  All code examples are provided as external Jupyter notebooks to keep the book itself concise and focused on concepts.

---

## Accessing and Running the Jupyter Notebooks

This repository contains Jupyter notebooks that illustrate and expand upon the topics covered in the book. Follow the steps below to install Jupyter and run the notebooks on your local machine.

### 1. Install Python

- **Windows or macOS**  
  Download and install the latest Python 3.x version from [python.org](https://www.python.org/downloads/).

- **Linux**  
  Use your distribution’s package manager (e.g., `apt-get install python3`) to install Python 3.

### 2. (Optional) Set Up a Virtual Environment

Although not strictly required, creating a virtual environment ensures your project dependencies do not conflict with other Python installations on your system.

- **Windows/macOS**  
  ```bash
  python -m venv myenv
  source myenv/bin/activate  # macOS/Linux
  myenv\Scripts\activate     # Windows
  ```

- **Linux**  
  ```bash
  python3 -m venv myenv
  source myenv/bin/activate
  ```

### 3. Install Jupyter Notebook

Once your environment is active, install Jupyter:
```bash
pip install jupyter
```

### 4. Download or Clone This Repository

To download or clone this repository, open a terminal and run:
```bash
git clone https://github.com/martyn-harris-bbk/JustEnoughDataScienceAndMachineLearning.git
```
Alternatively, you can download the zip file from GitHub’s web interface and extract it on your local machine.

### 5. Start Jupyter Notebook

Navigate to the repository folder and launch Jupyter Notebook:
```bash
cd JustEnoughDataScienceAndMachineLearning
jupyter notebook
```
This command will open the Jupyter Notebook interface in your default web browser.

### 6. Open and Explore the Notebooks

- Click on any notebook file (ending in `.ipynb`) to open it.  
- If any additional packages (e.g., `pandas`, `numpy`, `matplotlib`, `scikit-learn`) are not installed, install them as needed:
  ```bash
  pip install pandas numpy matplotlib scikit-learn
  ```
- Run the code cells in the notebook to replicate the examples discussed in the book.
