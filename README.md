# Data-Analytics-Capstone-Project
# Project Setup Guide

This guide provides instructions to set up and manage the Python virtual environment for this project.

---

## 📦 Prerequisites

- Python 3.8 or higher installed  
- (Optional but recommended) [pipx](https://pypa.github.io/pipx/) or a tool like [pyenv](https://github.com/pyenv/pyenv)

---

## 🛠️ Setting Up the Virtual Environment

### 1. Create a Virtual Environment

```bash
# Create the virtual environment in a folder named 'venv'
python -m venv venv
```

### 2. Activate the Virtual Environment
On Windows
``` bash
Copy
Edit
# Activate from Command Prompt
venv\Scripts\activate

# Or from PowerShell
.\venv\Scripts\Activate.ps1
```
On macOS / Linux
``` bash
Copy
Edit
source venv/bin/activate
```
📂 Installing Project Dependencies
After activating the environment:

``` bash
Copy
Edit
# Install required packages
pip install -r requirements.txt
```
```bash
Copy
Edit
pip freeze > requirements.txt
```
✅ Deactivating the Virtual Environment
To exit the virtual environment when you're done:

```bash
Copy
Edit
deactivate
```