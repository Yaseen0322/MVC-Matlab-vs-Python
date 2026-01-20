# MVC-Matlab-vs-Python
Matlab vs Python Multi-variable Calculus Computations (semester project)

## Project kickoff
To start the semester project, we should align on the scope, deliverables, and first-week setup. I suggest beginning with a short proposal that frames the comparison, selects representative multivariable calculus tasks, and defines how we will measure results.

### 1) Project goals
* Compare Matlab and Python for multivariable calculus computations in terms of:
  * Numerical accuracy and stability.
  * Performance (runtime, memory).
  * Developer ergonomics (code length, readability, libraries).
* Deliver a reproducible benchmark suite with clear write-ups and plots.

### 2) Proposed computational tasks
Select 4–6 representative problems that span symbolic and numeric workflows:
1. **Gradient, Jacobian, Hessian** for nonlinear scalar/vector fields.
2. **Multiple integrals** (double/triple integrals) with mixed bounds.
3. **Constrained optimization** using Lagrange multipliers and numeric solvers.
4. **Surface/volume calculations** with parametric surfaces.
5. **Vector calculus identities** (divergence, curl) verified numerically.

### 3) Tooling and environments
* **Matlab**: Symbolic Math Toolbox, Optimization Toolbox, base numeric routines.
* **Python**: NumPy, SciPy, SymPy, JAX (optional for autodiff comparisons).
* Reproducibility: lock versions, document OS and hardware, and provide scripts.

### 4) Evaluation plan
* **Accuracy**: compare against analytic results where available.
* **Performance**: standardize input sizes and report median runtime of multiple runs.
* **Ergonomics**: code length, clarity, and setup effort.

### 5) First-week deliverables
* A short **project proposal** (1–2 pages) with the task list and metrics.
* A **benchmark harness outline** (folder structure + stub scripts).
* Initial **literature scan** (3–5 references) on Matlab vs Python scientific computing.
