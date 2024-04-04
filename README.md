# Setup Instructions
## Environment
```
conda create --name med_ner python=3.10
conda activate med_ner
python -m ipykernel install --user --name med_ner
pip install pip-tools
```
## Install requirements

If adding new packages. Add to requirements.in file. then run
```
pip-compile requirements.in
```
If installing existing packages.
```
pip install -r requirements.txt
```