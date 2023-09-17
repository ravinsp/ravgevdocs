### Local build

```
python -m sphinx -T -E -b html -d _build/doctrees -D language=en docs/source/ html
```

## Preview

```
cd html
python -m http.server 8080
```