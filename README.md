# Mi proyecto Python - CI demo

Demo de repositorio Python con GitHub Actions que ejecuta 3 etapas: build, test y deploy (simulado).

## Cómo ejecutar localmente
```bash
python -m venv .venv
source .venv/bin/activate  
pip install --upgrade pip
pip install -e '.[test]'
pytest -q
