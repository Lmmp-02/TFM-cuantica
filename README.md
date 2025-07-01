# Quantum and Classical Portfolio Optimization

Este proyecto explora distintos enfoques para la optimización de carteras financieras utilizando tanto métodos clásicos como aproximaciones cuánticas. Utiliza un conjunto de datos histórico de la bolsa de valores para comparar la eficiencia de ambos modelos.

## Estructura del Proyecto

```
├── dataset/                          # Archivos CSV con datos históricos de precios de acciones
│ ├── all_stocks_5yr.csv
│ └── stocks_cleaned.csv
├── notebooks/                        # Notebooks con los distintos experimentos
│ ├── Classical_Approximation.ipynb
│ ├── Quantum_Approximation.ipynb
│ └── Preprocess_Stocks.ipynb
├── LICENSE                           # Licencia del proyecto
└── README.md
```

## Notebooks

- `Preprocess_Stocks.ipynb`: Limpieza y preparación del dataset original (`all_stocks_5yr.csv`) para su análisis.
- `Classical_Approximation.ipynb`: Implementación de un modelo clásico de optimización de carteras (p.ej. media-varianza).
- `Quantum_Approximation.ipynb`: Simulación de una aproximación cuántica a la optimización de carteras utilizando distintas técnicas.


## Dataset

Los datos provienen de un archivo CSV (`all_stocks_5yr.csv`) que contiene precios históricos de acciones del S&P 500 durante 5 años. El archivo `stocks_cleaned.csv` contiene una versión depurada y lista para su análisis.

## Licencia

Este proyecto está licenciado bajo los términos de la licencia MIT. Consulta el archivo `LICENSE` para más información.