# Package name

Write package short description here.

# Template customization

Please change :
- [ ] pyproject.toml package_name
- [ ] Create package_name directory with at least `__init__.py` file
- [ ] Update `README.md`

# Template directory structure

- package_name/ - Insert package code here
- tests/ - Insert unit tests here
- scripts/ - Insert scripts here
- images/ - If this is CV/AI repository then insert images here

# Installation : Developer

Use poetry to install the package in development mode.

```bash
git clone {URL}
poetry env use python3.11
poetry install
```



# Testing   

Run the tests using pytest.

# Release

Github workflow is created to automatically release the package to PyPI when a new tag "vX.X.X" (example v1.0.0) is pushed to the main branch. 

