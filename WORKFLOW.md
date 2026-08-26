## Here is the command for creating a Python project with environement (PowerShell) :
1. Go to the place where you want to creat the project [(How)](https://github.com/ShmelSys/Tools/blob/main/Shell_commands.md)
2.  Write:
```
uv init my_python_project
cd my_python_project
md data
```
3. Download the libraries:
```
uv add ...
```
4. Make the code work with all the functions:
```
uv run python -i code_generetor.py
```

## The old way is:
1. Go to the place where you want to creat the project [(How)](https://github.com/ShmelSys/Tools/blob/main/Shell_commands.md)
2. Write:
```
python -m venv venv

ni requirements.txt, README.md, .gitignore

md data, scripts

"venv/" > .gitignore

"# Data Cleaning`n1. python -m venv venv`n2. .\venv\Scripts\Activate.ps1`n3. pip install -r requirements.txt" > README.md

.\venv\Scripts\Activate.ps1

```
3. Download the libraries:
```pip install ...```
4. For quitting the .venv, write `deactivate`.
