[![Pylint](https://github.com/EncryptEx/GPS-CI-lab/actions/workflows/linter.yml/badge.svg?branch=master)](https://github.com/EncryptEx/GPS-CI-lab/actions/workflows/linter.yml)

# Gestió de Projectes de Software 

2025-26 QT - Grup 21

Pràctica sobre Integració Contínua amb Github Actions.

## Funcionalitats i millores de la GitHub Action
- 🔁 Integració contínua automàtica a cada push.
- 🧹 Anàlisi de qualitat del codi amb Pylint abans d’executar els tests.
- ⛔ Els tests només s’executen si el lint és correcte.
- 🐳 Execució en contenidors Docker amb imatges oficials de Python.
- 🧪 Tests en diverses versions de Python: 3.8, 3.9 i 3.10.
- ❌ Si fallen els tests en una versió, les següents no s’executen, evitant execucions innecessàries i estalviant minuts d'execució.
- ⚡ Ús de cache de dependències per reduir el temps d’execució.
- 📊 Càlcul de cobertura de codi amb coverage.
- 📁 Informe HTML de cobertura disponible com a artifact.
- 🔍 L’informe de cobertura es genera encara que algun test falli.
- 👀 S'ha afegit una branch_protection rule a master per tal de no poder fer push directament, cal passar per Pull Request i passar la action satisfactòriament.
