`conda create --prefix ./env` //run in terminal at project folder
`conda activate /Users/path/to/env` // mengubah base ke folder project ini
`conda deactivate` //mengubah 'base' ke default
`conda env export --prefix /Users/path/to/env > environment.yml` //untuk export nama nama package yang dipakai ke environment.yml
`conda env create --file environment.yml --name env_from_file` //untuk install package dari environment.yml
