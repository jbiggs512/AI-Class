# Project Setup Guide

## Westcode Workspace

JIDE-PyTorch-wCUDA

* Only your workspace folder is persistent, all other directories will be wiped periodically.
* Access the Jupyter web server in your browser via the "Ports" tab in code-server.
* Please make frequent backups of your code, either download as a ZIP file or push to GitHub.

## Local Development Environment

This project uses a **Python virtual environment (venv)** to keep dependencies isolated.

### Activating the Virtual Environment

Before running any code or installing packages, make sure the virtual environment is active.

```powershell
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
deactivate
```

### Updating the Virtual Environment

Activate the environment, install dependancies as normal then update requirements.txt

```powershell
.\.venv\Scripts\Activate.ps1
```

* Install / Update dependancies

Now, update requirements.txt and deactivate

```powershell
pip freeze > requirements.txt
deactivate
```
