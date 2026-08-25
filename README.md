<h1 align="center">🔬 Scientific Python & Digital Image Processing Journey</h1>

<h3 align="center">
  A Step-by-Step Learning Roadmap for Scientific Computing, Computer Vision, and Medical Image Analysis
</h3>

<p align="center">
  <a href="https://github.com/Hoomansarabi/python-scientific-journey">
    <img src="https://img.shields.io/badge/Python-Scientific%20Computing-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Scientific Computing" />
  </a>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/Matplotlib-Scientific%20Visualization-11557C?style=for-the-badge&logo=python&logoColor=white" alt="Matplotlib" />
  <img src="https://img.shields.io/badge/Computer%20Vision-FF6F00?style=for-the-badge&logo=opencv&logoColor=white" alt="Computer Vision" />
</p>

---

## 👋 About This Repository

This repository documents my hands-on journey from fundamental Python programming to scientific computing, digital image processing, computer vision, and medical image analysis.

The learning process is organized as a sequence of practical exercises. Each section introduces an important concept, implements it with Python, and connects the underlying mathematics to real scientific and engineering applications.

The central idea of this journey is the **matrix mindset**:

> Digital images are numerical arrays, and understanding their mathematical structure is the foundation of image processing and computer vision.

This repository is designed for students, researchers, and developers who want to build a strong foundation in scientific Python through clear, reproducible, and progressively structured examples.

---

## 🎯 Learning Objectives

- Learn how scientific problems can be represented using numerical arrays and matrices.
- Master vectorized, slicing,NumPy` instead of relying on inefficient Python loops.
- Understand array dimensions, indexing, slicing, broadcasting, and axes.
- Create mathematical models and scientific visualizations with `Matplotlib`.
- Understand grayscale images as two-dimensional intensity matrices.
- Generate synthetic images, gradients, geometric shapes, and binary masks.
- Implement fundamental image transformations from scratch.
- Connect linear algebra and numerical computation to digital image processing.
- Develop clean, readable, and reproducible code suitable for research and education.
- Build a foundation for future work in computer vision and medical image analysis.

---

## 📚 Repository Roadmap

### 1. NumPy Foundations

Directory: [`01_numpy_basics`](./01_numpy_basics)

This section introduces the numerical foundations required for scientific computing and image processing.

Topics include:

- Creating one-dimensional and multidimensional arrays.
- Vectorized arithmetic operations.
- Element-wise addition, subtraction, multiplication, and division.
- Scalar operations and broadcasting.
- Boolean masking and conditional filtering.
- Selecting values based on logical conditions.
- Two-dimensional matrices and image-like data structures.
- Array indexing and slicing.
- Understanding rows, columns, and matrix dimensions.
- Aggregation operations using `axis=0` and `axis=1`.

The main goal is to replace a loop-based way of thinking with an efficient array-based approach.

---

### 2. Scientific Visualization

Directory: [`02_matplotlib_visualization`](./02_matplotlib_visualization)

This section focuses on visualizing mathematical functions and scientific data.

Topics include:

- Creating numerical domains with `np.linspace`.
- Sampling continuous mathematical functions.
- Plotting the function:

  $$y = x^2$$

- Comparing trigonometric functions such as:

  $$y_1 = \sin(x)$$

  $$y_2 = \cos(x)$$

- Creating multiple plots in a single figure.
- Customizing colors, line styles, labels, legends, and titles.
- Using mathematical notation and LaTeX labels in scientific figures.
- Preparing clear and interpretable visualizations for research and education.

Visualization is treated as an analytical tool, not only as a presentation method.

---

### 3. Digital Image Processing Fundamentals

Directory: [`03_image_processing_fundamentals`](./03_image_processing_fundamentals)

This section builds a bridge between numerical arrays and digital images.

Topics include:

- Representing grayscale images as two-dimensional NumPy arrays.
- Generating synthetic intensity gradients.
- Understanding pixel intensity values.
- Constructing geometric shapes using matrix slicing.
- Creating rectangular regions and binary masks.
- Performing spatial operations on selected image regions.
- Implementing point intensity transformations.
- Applying the negative image transformation:

  $$I_{\text{neg}} = 255 - I$$

These exercises establish the basic concepts required for more advanced topics such as filtering, segmentation, feature extraction, and image classification.

---

## 🧠 Learning Approach

Each exercise follows a consistent educational structure:

1. **Concept**  
   A concise explanation of the mathematical or computational idea.

2. **Implementation**  
   A direct Python implementation using scientific libraries.

3. **Visualization or Output**  
   Numerical results, printed arrays, or graphical representations.

4. **Interpretation**  
   An explanation of what the output means and how it relates to the underlying concept.

5. **Research Connection**  
   A discussion of how the topic is used in scientific computing, computer vision, or medical image analysis.

This structure is intended to make the repository useful both as a personal learning log and as a reference for other learners.

---

## 🛠️ Technologies and Tools

### Scientific Computing and Visualization

- Python
- NumPy
- Matplotlib

### Future Direction

The next stages of this journey will gradually move toward:

- OpenCV
- Image loading and color-space conversion
- Image filtering and enhancement
- Edge detection
- Image segmentation
- Feature extraction
- Convolutional Neural Networks
- Vision Transformers
- Medical image analysis
- Skin cancer detection

---

## 🚀 Getting Started

### 1. Clone the Repository

First, clone the repository and move into the project directory:
```bash
git clone https://github.com/Hoomansarabi/python-scientific-journey.git
cd python-scientific-journey
```
---

### 2. Create a Virtual Environment

Using a virtual environment is recommended to keep the project's dependencies isolated from your system-wide Python installation.

#### Windows
Create a virtual environment:
```bash
python -m venv venv
````

#### Activate the environment:
Command Prompt (CMD):
```bash
venv\Scripts\activate
```

#### PowerShell:
```bash
venv\Scripts\Activate.ps1
```

#### If PowerShell displays an execution-policy error, run the following command once:
```bash
> Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
> 
```

#### Linux / macOS
Create and activate the virtual environment:
```bash
python3 -m venv venv
source venv/bin/activate
```
When the virtual environment is active, (venv) should appear at the beginning of your terminal prompt.

---

### 3. Install Dependencies
Install all required Python packages using:
```bash
pip install -r requirements.txt
```
---

### 4. Run the Exercises
Run a NumPy exercise:
```bash
python 01_numpy_basics/01_arithmetic.py
```

Run the matrix and axes exercise:
```bash
python 01_numpy_basics/03_matrices_and_axes.py
```

Run the visualization exercise:
```bash
python 02_matplotlib_visualization/01_trigonometric_plots.py
```

Run the image-processing exercise:
```bash
python 03_image_processing_fundamentals/01_shapes_and_negative.py
```
---
### 5. Deactivate the Virtual Environment
When you finish working on the project, deactivate the environment with:

```bash
deactivate
```



