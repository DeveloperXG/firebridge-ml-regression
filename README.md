# firebridge-ml-regression
XGBoost regression model trained on IoT device telemetry to predict water usage (synthetic target) based on temperature, energy consumption, signal strength, and device metadata.

## Setup & Run

1. **Create a virtual environment**

```bash
python -m venv .venv
```
2. **Activate the virtual environment**

On Windows
```bash
.venv\Scripts\Activate
```

On macOS/Linux
```bash
source .venv/bin/activate
```
3. **Install dependencies**
```bash
pip install -r requirements.txt
```
4. **Run the notebook**
   
Select your activated virtual environment as the kernel in Jupyter Notebook/VS Code, then run the code.
