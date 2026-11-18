# proyecto_perfumes

## Exploración del mundo de los perfumes

### Descripción

Análisis exploratorio de un dataset de Fragrantica con más de 24 mil perfumes.
El objetivo es detectar diferencias entre fragancias masculinas, femeninas y unisex,
y comprobar si los datos confirman las percepciones habituales sobre el mercado de la perfumería.

## Hipótesis analizadas

| # | Hipótesis | Resultado |
|---|-----------|-----------|
| H1 | Los perfumes femeninos dominan el catálogo | ✓ Confirmada |
| H2 | Los masculinos son más amaderados; los femeninos, más florales | ⚠︎ Parcialmente confirmada |
| H3 | Los unisex se parecen más a los masculinos que a los femeninos | ✓ Confirmada |
| H4 | Los 10 perfumes más populares son de origen francés | ⚠︎ Parcialmente confirmada |

## Estructura

proyecto_eda
├──proyecto_perfumes
    ├──src
        ├── data
        ├── perfumes_limpio.csv
        └──perfumes.csv
    └── notebooks
        ├── limpieza.ipynb
        ├── eda.ipynb
    └──utils
        └── memoria.ipynb
├──README.md

## Herramientas

Python, Pandas, Matplotlib,Jupyter Notebook, VS Code

## Conclusiones

Los datos confirman una clara diferenciación por género tanto en volumen como en perfil olfativo.
Los perfumes unisex se sitúan más cerca del masculino, y Francia domina entre los más valorados,
aunque no de forma exclusiva.