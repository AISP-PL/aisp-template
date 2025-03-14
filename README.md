# Template : How to start and customize?

- [ ] Create new repository from this template
- [ ] pyproject.toml rename package_name
- [ ] Rename aisp_template directory to package_name
- [ ] Update `README.md`

# Template directory structure

- package_name/ - Insert package code here
- tests/ - Insert unit tests here
- scripts/ - Insert scripts here
- images/ - If this is CV/AI repository then insert images here

# Package name

Write package short description here.

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

