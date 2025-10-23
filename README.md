# AURA-Model Repository

This repository contains all **ML models**, **training scripts**, and **notebooks** for the **AURA (Auditory Urban Reality Assistant)** project.

---

## Quick Start (Local Setup)

Follow these steps to set up your local development environment.  
> **Note:** We do **not** use Docker for this repository.

---

### 1. Prerequisites

Make sure you have the following installed:

- **Python 3.10** – Download from [python.org](https://www.python.org/downloads/)
- **Git** – Install from [git-scm.com](https://git-scm.com/)

---

### 2. Clone the Repository

```bash
git clone https://github.com/AuraGuide/AURA-Model.git
cd AURA-Model
```

---

### 3. Create and Activate Virtual Environment

We use `venv` to keep project dependencies isolated.

```bash
# Create the virtual environment (named 'venv')
python -m venv venv
```

#### Activate the environment

**Windows (PowerShell/CMD):**
```bash
.\venv\Scripts\activate
```

**macOS/Linux:**
```bash
source venv/bin/activate
```

> Your terminal prompt should now show `(venv)`.

---

### 4. Install Dependencies

Install all required Python packages using the pinned versions file:

```bash
pip install -r requirements.txt
```

---

### 5. Launch Jupyter Lab

You are now ready to work. Launch **Jupyter Lab** to start experimenting:

```bash
jupyter lab
```

---

### 6. Git Workflow

Follow this Git workflow for every new feature or task:

```bash
# Make sure you're on the latest main branch
git checkout main
git pull origin main

# Create a new feature branch
git checkout -b feature/your-new-feature

# ...do your work...
git commit -m "Describe your changes"
git push origin feature/your-new-feature
```

Then open a **Pull Request** on GitHub.
