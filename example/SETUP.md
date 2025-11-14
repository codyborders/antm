# Setup Instructions

## Prerequisites

- Python 3.11 or higher
- pip (comes with Python)

## Installation

### Recommended: Use a Virtual Environment

This prevents common issues with system Python installations (especially on macOS):

1. Clone the repository:
```bash
git clone https://github.com/theoryvc/modeler-hackathon-starter.git
cd modeler-hackathon-starter
cd example
```

2. Create and activate a virtual environment:
```bash
python3 -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. (Optional) Register the environment as a Jupyter kernel:
```bash
python -m ipykernel install --user --name "modeler-starter" --display-name "Python 3 (Modeler Starter)"
```

5. Launch the notebook:
```bash
jupyter notebook tools_guide.ipynb
```
