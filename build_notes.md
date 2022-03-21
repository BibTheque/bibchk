# venv

python -m venv pyenv
pip install build twine wheel

# build

python -m build

# upload

python -m twine upload dist/*
