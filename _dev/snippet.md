### Export

1. Check export statement to `.py` file

```
#| default_exp <module-name>
```

2. Run Export

```zsh
nbdev_export
# Then Install a project in editable mode 
pip install -e .
```

### Preview

```zsh
nbdev_preview
```

> This command must run inside the directory where `_quarto.yml` lives.



### Test

```zsh
nbdev_test
```

### Generate README

```zsh
nbdev_docs
```

### Build & Upload

```zsh
# Create Dist
python -m build

# To testpypi
python3 -m twine upload --repository testpypi dist/*
```
