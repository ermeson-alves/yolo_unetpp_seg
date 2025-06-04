# SETUP

#### Install UV utility:
```
# On macOS and Linux.
curl -LsSf https://astral.sh/uv/install.sh | sh
```

```
# On Windows.
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

#### Synchronize the project environment
```
uv sync
```

#### Activate the virtual environment
```
# On Linux
source .venv/bin/activate
```

Windows Script Execution Policy Configuration:
```
# On Windows Powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

Activating the virtual environment
```
# On Windows Powershell
.venv\Scripts\activate.ps1
```
```
# On Windows cmd
.venv\Scripts\activate.bat
```