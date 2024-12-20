# Proyecto de Pruebas de API y E2E

Este repositorio contiene:

- **Archivos de Postman**: Para pruebas de API.
- **Documentación en LaTeX**: Descripción detallada de las pruebas.

## Uso

1. **Clonar el repositorio**:

   ```bash
   git clone https://github.com/OscarCampohermoso/gestion-calidad-3er-parcial.git
   ```

2. **Ejecutar pruebas con Newman**:

   ```bash
   cd postman-files
   newman run collections/API-testing-OscarCampohermoso.postman_collection.json -e environments/QAenv-OscarCampohermoso.postman_environment.json
   ```

3. **Generar documentación**:

   ```bash
   cd latex-document
   pdflatex main.tex
   ```
