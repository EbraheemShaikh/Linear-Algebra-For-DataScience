# 📈 Progress Log: Linear Algebra for Data Science

### 📅 July 5, 2025

**Completed:**  
- 📘 Khan Academy – Lesson 5, Lecture 4: *Vector Triangle Inequality*

**Concepts Covered:**  
- Expanded and simplified `||u + v||²`
- Used dot product and Cauchy-Schwarz inequality
- Proved: `||u + v|| ≤ ||u|| + ||v||`
- Understood the condition when equality holds (collinear vectors)

**Notebook:**  
[08_vector_triangle_inequality.ipynb](https://github.com/EbraheemShaikh/Linear-Algebra-For-DataScience/blob/main/08_vector_triangle_inequality.ipynb)


## 🗓️ June 30, 2025

### 📘 Watched:
- **Lecture 3 of Lesson 5 – Cauchy-Schwarz Inequality**  
  *(Khan Academy – Linear Algebra)*

### 🧠 Concepts Covered:
- **Cauchy-Schwarz Inequality**:  
  `|u · v| ≤ ||u|| × ||v||`
- **Equality Case**: Occurs only when one vector is a scalar multiple of the other
- **Proof Technique**:
  - Defined the function: `f(t) = ||tv − u||²`, which is always ≥ 0
  - Expanded using dot product rules:
    ```
    f(t) = t²||v||² − 2t(u·v) + ||u||²
    ```
  - Applied the discriminant condition from algebra:  
    `b² − 4ac ≤ 0` to ensure positivity
  - Derived: `(u · v)² ≤ ||u||² × ||v||²`, then took square root

### 🧮 Notebook Created:
- [`07_cauchy_schwarz_inequality.ipynb`](https://github.com/EbraheemShaikh/Linear-Algebra-For-DataScience/blob/main/07_cauchy_schwarz_inequality.ipynb)  
  ✅ Contains both **LaTeX styling** and **simple math explanations** for clarity

---


### 📅 July 1, 2025
- ✅ Completed Khan Academy – Lesson 5 (Vector Dot Product)
  - Watched Lectures 1 & 2:
    - Learned how to compute **dot product** and **vector length**
    - Proved dot product properties: **commutative, distributive, scalar multiplication**
    - Understood that **||v|| = √(v·v)** (norm from dot product)
- 📓 Created & uploaded notebook: `06_dot_product_and_vector_length.ipynb`
- 📌 Note: Watched Cauchy-Schwarz Inequality (Lecture 3), but will complete the notebook tomorrow


### 📅 June 30, 2025
- ✅ Completed Khan Academy: Lesson 4 – Basis of a Subspace (Lecture 2)
- 🧠 Learned:
  - A **basis** is a set of linearly independent vectors that spans a subspace
  - Every vector in the subspace has a **unique** representation using the basis
  - Subspaces can have **multiple bases**, including the standard basis
- 🧮 Example:
  - Verified that {[2, 3], [7, 0]} forms a basis of ℝ²
  - Compared it with the standard basis {[1, 0], [0, 1]}
- 📓 Created and uploaded notebook: `05_basis_of_subspace.ipynb`


### 📅 June 28, 2025
- ✅ Completed Khan Academy: Lesson 4 – Linear Subspaces (Lecture 1)
- 🧠 Learned:
  - Three essential conditions for a subspace:
    1. Contains zero vector
    2. Closed under scalar multiplication
    3. Closed under vector addition
  - Tested subspace conditions through examples:
    - Zero vector subspace in ℝ³ ✅
    - Non-subspace due to scalar violation ❌
    - Subspace formed by Span{v₁, v₂, v₃} ✅
- 📓 Created and uploaded notebook: `04_subspaces.ipynb`
  - Includes well-explained markdown and NumPy examples


### 📅 June 27, 2025
- ✅ Completed Khan Academy: Lesson 3 – Linear Independence (Lectures 2 & 3)
- 🧠 Learned:
  - Formal test for linear dependence using vector equations
  - How to solve a * v₁ + b * v₂ + ... = 0 to determine if a set is dependent or independent
  - Span of a 3D vector set and its relation to linear independence
- 📓 Created and uploaded: `03_linear_independence_examples.ipynb`
  - Includes 2D and 3D examples with NumPy and vector visualizations

### 📅 June 26, 2025
- ✅ Watched Khan Academy:
  - Lesson 2: Linear Combinations and Span
  - Lesson 3 (Lecture 1): Introduction to Linear Independence
- 📓 Created and uploaded notebook: `02_linear_combinations_span_independence.ipynb`
  - Explained span and independence with code examples and visualizations using NumPy and Matplotlib
- 🧠 Concepts covered:
  - Linear combinations
  - Span with formal set definition
  - Linear dependence and redundancy
  - Linear independence intuition and detection


## 📅 June 12, 2025

### 🧠 Khan Academy - Linear Algebra
- ✅ Completed **Lesson 1: Vectors and Spaces**
  - Topics covered:
    - What is a vector (magnitude & direction)
    - Real coordinate space and n-dimensional tuples
    - Vector addition, subtraction, and scalar multiplication with visual intuition
    - Introduction to unit vectors and the concepts of **i** and **j**
    - Parametric representation of lines and position vectors
  - Completed 3 small assessments to reinforce understanding
  - Took handwritten notes to clarify difficult concepts (especially parametric lines)

### 💻 Python Practice
- ✅ Created a well-structured Google Colab notebook: `01_vectors_and_geometry.ipynb`
  - Summarized all key concepts from Lesson 1 in markdown
  - Added NumPy code examples for:
    - Vector addition, subtraction, and scalar multiplication
  - Uploaded to GitHub:
    - 📁 Repository: [Linear-Algebra-For-DataScience](https://github.com/EbraheemShaikh/Linear-Algebra-For-DataScience)
    - 📄 Notebook: [`01_vectors_and_geometry.ipynb`](https://github.com/EbraheemShaikh/Linear-Algebra-For-DataScience/blob/main/01_vectors_and_geometry.ipynb)

### 📌 Plan Ahead
- Will continue to Lesson 2 of Khan Academy tomorrow
- Will begin Coursera’s NumPy course once arrays/matrices appear in Khan lectures


### 📅 June 10, 2025
- ✅ Planned learning path: Khan Academy + Coursera + FreeCodeCamp
- ✅ Created new Gmail for Colab + GitHub setup
- ✅ Set up GitHub and Google Colab
- ✅ Created GitHub repo
- ✅ Linked GitHub with Colab
- ✅ Created repo: `Linear-Algebra-For-Data-Science`

