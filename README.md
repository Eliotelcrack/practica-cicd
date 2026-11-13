# practica-cicd

Práctica guiada EA3 — AUY1102 Ciclo de Vida del Software.

Pipeline de Integración Continua con GitHub Actions sobre una calculadora en Python.

## Contenido

- `calculadora.py`: funciones sumar, restar, multiplicar y dividir.
- `test_calculadora.py`: pruebas automáticas con pytest.
- `.github/workflows/pull_request.yml`: workflow de CI que se ejecuta en cada
  push y pull request a la rama `master`: descarga el código, instala Python 3.12,
  instala pytest y ejecuta las pruebas.
