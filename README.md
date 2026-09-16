# Data Science Tools and Ecosystem

Proyecto final del curso **Tools for Data Science**, parte del programa
*Data Science Foundations* de IBM en Coursera.

El notebook documenta el ecosistema de herramientas del análisis de datos
(lenguajes, librerías y entornos) y resuelve los ejercicios de evaluación
de expresiones aritméticas en Python que pide el curso.

## Contenido

| Sección | Descripción |
|---|---|
| Lenguajes | Lenguajes habituales en ciencia de datos: Python, R, SQL, Julia, Scala |
| Librerías | Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Keras, TensorFlow, PyTorch |
| Herramientas | Tabla comparativa: Jupyter, RStudio, Apache Spark, GitHub, Watson Studio |
| Ejercicios | Evaluación de expresiones aritméticas y conversión de unidades en Python |

## Estructura

```
.
├── notebooks/
│   └── 01-herramientas-y-ecosistema-data-science.ipynb
├── requirements.txt
└── README.md
```

La convención `NN-descripcion` en `notebooks/` numera los cuadernos por orden
de lectura, de modo que el repositorio admite nuevos análisis sin reorganizarse.

## Cómo ejecutarlo

```bash
python -m venv .venv
source .venv/bin/activate      # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab notebooks/
```

El notebook no depende de datasets externos: se ejecuta de principio a fin
sin descargar nada.

## Tecnologías

Python · Jupyter Notebook

## Autor

Juan Sebastián Torres Sánchez
