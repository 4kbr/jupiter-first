`conda create --prefix ./env` //run in terminal at project folder
`conda activate /Users/path/to/env` // mengubah base ke folder project ini
`conda deactivate` //mengubah 'base' ke default
`conda env export --prefix /Users/path/to/env > environment.yml` //untuk export nama nama package yang dipakai ke environment.yml
`conda env create --file environment.yml --name env_from_file` //untuk install package dari environment.yml

or

use pip:

1. run `python3 -m venv .venv` for initial envirovment
2. run `pip install -r requirements.txt` for install all requirements package
