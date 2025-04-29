
## SEALS Project Notebook

This repository contains the `seals.ipynb` notebook, which requires a specific Conda environment for correct execution. Follow the steps below to recreate the environment and run the notebook.

### 📦 Requirements

- [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://www.anaconda.com/)
- Python 3.8 or higher (unless specified otherwise)

### 🛠️ Setup Instructions

#### 1. Clone the repository (if applicable)
```bash
git clone https://github.com/your-username/seals-project.git
cd seals-project
```

#### 2. Create the Conda environment
```bash
conda create --name seals python=3.11
```

#### 3. Activate the environment
```bash
conda activate seals
```

#### 4. Install required packages

If you have an `environment.yml` file (recommended), install with:
```bash
conda env update --file environment.yml
```

Otherwise, manually install typical dependencies:
```bash
conda install jupyter pandas numpy matplotlib seaborn
```
(Include any additional packages used in the notebook.)

#### 5. Launch Jupyter Notebook
```bash
jupyter notebook Spectogram.ipynb
```

---

