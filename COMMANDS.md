
### Create virtual environment
python3 -m venv .venv
virtualenv --python="/usr/local/bin/python3.10" .venv

### Activate virtual environment
source .venv/bin/activate (zsh)
.venv/bin/Activate.ps1 (pwsh)

### Install packages
pip install -r requirements.txt