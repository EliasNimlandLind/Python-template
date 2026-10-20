# Python template

# About 
This is a minimalistic Python template.

## Setup
1. Navigate to the project root directory. 
2. Create a virtual environment through the execution of:

```bash
python -m venv .venv
```

3. Activate the environment through the execution of one of the commandsfound below:
    - On Windows PowerShell:

    ```powershell
    .venv\Scripts\Activate.ps1
    ```

    - On Linux and macOS:

    ```bash
    source .venv/bin/activate
    ```
3. Install dependencies by adding each one to `requirements.txt` and exeute:
```bash
python -m pip install -r requirements.txt
```
> The project will be installed in editable mode, i.e. changes do not require reinstallation, if `-e .[dev]` is kept in `requirements.txt`.
4. Update `pyproject.toml` according to the project.

## Usage
The execution of the command found below starts the application:
```bash
python main.py
```
