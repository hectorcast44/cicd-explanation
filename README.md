# CI/CD Explanation & Workshop

Repositorio de ejemplo para la explicación e implementación de prácticas de CI/CD utilizando GitHub Actions, Python y Docker.

## Estructura del Proyecto

- `src/`: Contiene el código fuente (`main.py`), las pruebas (`tests.py`) y las dependencias (`requirements.txt`).
- `.github/workflows/`: Workflows automatizados de GitHub Actions para pruebas y compilación.
- `Dockerfile`: Configuración para construir la imagen del contenedor de la aplicación.

## Requisitos y Ejecución Local

1. Instalar dependencias:
   ```bash
   pip install -r src/requirements.txt
   ```

2. Ejecutar las pruebas:
   ```bash
   pytest src/tests.py
   ```
