# Projects

This directory contains the hands-on projects and Jupyter notebooks for the AI Learning Lab.

## Environment Setup

To keep all projects organized and dependencies managed, we use a single virtual environment named `ai-learning` for the entire repository. 

Follow these instructions to set it up:

### 1. Create the Virtual Environment
Open your terminal in the root directory of the repository (where `requirements.txt` is located) and run:
```powershell
python -m venv ai-learning
```

### 2. Activate the Virtual Environment
Before installing packages or running notebooks, activate the environment:

**On Windows:**
```powershell
.\ai-learning\Scripts\activate
```

**On macOS/Linux (if applicable):**
```bash
source ai-learning/bin/activate
```

### 3. Install Dependencies
Once the environment is active (you should see `(ai-learning)` in your terminal prompt), install the required libraries:
```powershell
pip install -r requirements.txt
```

### 4. Start Jupyter Lab
You can now start working on the projects by launching Jupyter:
```powershell
jupyter lab
```
