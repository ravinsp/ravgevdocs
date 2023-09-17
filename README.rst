## Local setup

```
python -m pip install --upgrade --no-cache-dir sphinx readthedocs-sphinx-ext myst-parser
python -m pip install --exists-action=w --no-cache-dir -r docs/requirements.txt
```

### Local build

```
python -m sphinx -T -E -b html -d _build/doctrees -D language=en docs/source/ html
```

## Preview

```
cd html
python -m http.server 8080
```