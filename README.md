# SDM Project Simulation

This project contains a Jupyter notebook for simulation purposes.

## Setup Instructions

To run the Jupyter notebook `simulation.ipynb`, follow these steps to initialize a Python kernel.

### Prerequisites

- Python 3.x installed on your system
- pip (Python package installer)

### Option 1: Using venv and pip (Default)

1. **Create a virtual environment** (recommended to isolate dependencies):

   ```
   python -m venv venv
   ```

2. **Activate the virtual environment**:

   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```

3. **Install required packages**:

   ```
   pip install -r requirements.txt
   ```

4. **Install ipykernel** (for Jupyter kernel support):

   ```
   pip install ipykernel
   ```

5. **Create and install the kernel**:
   ```
   python -m ipykernel install --user --name=sdm-project-kernel --display-name="SDM Project Kernel"
   ```

### Option 2: Using Anaconda

1. **Prerequisites**: Anaconda or Miniconda installed.

2. **Create a conda environment**:

   ```
   conda create -n sdm-env python=3.x
   ```

3. **Activate the environment**:

   ```
   conda activate sdm-env
   ```

4. **Install required packages**:

   ```
   pip install -r requirements.txt
   ```

5. **Install ipykernel**:

   ```
   conda install ipykernel
   ```

6. **Create and install the kernel**:
   ```
   python -m ipykernel install --user --name=sdm-env --display-name="SDM Project Kernel (Conda)"
   ```

### Option 3: Using uv

1. **Prerequisites**: uv installed (install via `pip install uv` or from https://github.com/astral-sh/uv).

2. **Create a virtual environment**:

   ```
   uv venv
   ```

3. **Activate the virtual environment**:

   - On Windows:
     ```
     .venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source .venv/bin/activate
     ```

4. **Install required packages**:

   ```
   uv pip install -r requirements.txt
   ```

5. **Install ipykernel**:

   ```
   uv pip install ipykernel
   ```

6. **Create and install the kernel**:

   ```
   python -m ipykernel install --user --name=sdm-uv-kernel --display-name="SDM Project Kernel (uv)"
   ```

7. **Open the notebook**:
   - Open `simulation.ipynb` in VS Code or Jupyter Notebook.
   - Select the appropriate kernel (e.g., "SDM Project Kernel") from the kernel selection menu.

### Running the Notebook

Once the kernel is set up, you can run the cells in `simulation.ipynb` to execute the simulation.

### Deactivating the Environment

When done, deactivate the virtual environment:

```
deactivate
```
