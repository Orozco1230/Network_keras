# Neural Network Keras
This project uses Keras to implement a simple neural network. Here you will find the steps to clone and run the project.

## Prerequisites
- Python 3.10 or higher
- Git
- A virtual environment (recommended)

## Clone the Repository
To clone the project, run the following command in your terminal:

```bash
git clone https://github.com/LorenzoBlas/Neural_network_keras_BlasBalderas.git
```

## Install Dependencies
1. **Create a Virtual Environment:**
   ```bash
   python3 -m venv .venv
   ```

2. **Activate the Virtual Environment:**
   - On Linux/Mac:
     ```bash
     source .venv/bin/activate
     ```
   - On Windows:
     ```cmd
     .\.venv\Scripts\activate
     ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Run the Project
To run the project, simply execute the `main.py` file:

```bash
python main.py
```

## Troubleshooting Common Issues

### 1. Dependency Installation Errors
- **`requirements.txt` not found:**
  - Ensure that the `requirements.txt` file is in the correct directory.
- **Permission issues:**
  - Try running the command with `sudo` if necessary.

### 2. Import Errors
- **Module not found (e.g., `numpy` or `keras`):**
  - Ensure that the virtual environment is activated and that dependencies are installed correctly.

### 3. Git Issues
- **Error cloning or pushing changes:**
  - Check that your internet connection is stable and that there are no issues with your GitHub account.

### 4. Project Execution Errors
- **CUDA warning messages:**
  - These messages usually appear if you don't have an NVIDIA GPU configured. You can ignore them if you're not using the GPU.
from Perplexity: pplx.ai/share
