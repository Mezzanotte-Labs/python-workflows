# python-workflows

This repository is used to run our Python workflow for all Python projects

WARNING: Any edits to this repository will affect ALL Python projects

# Example

Very straight foward use example:

```yaml
name: Python Lint


on:
  pull_request:
    branches:
      "**"


jobs:
  tasks:
    uses: Mezzanotte-Labs/python-workflows/.github/workflows/python_check.yml@main
```
