# ONE-Challenge-2
Segundo proyecto de ONE

# Proyecto **Alura Store** – Análisis de Ventas

## 📝 Propósito

Este repositorio documenta el análisis exploratorio y descriptivo de los datos de ventas de **Alura Store Latam** con el objetivo de responder a la pregunta «¿En qué tienda debería vender el Sr. Juan?».  Para ello se evaluaron ingresos, popularidad de categorías y productos, satisfacción de clientes, costos logísticos y el componente geográfico de las ventas.

## 📦 Estructura del proyecto

```
/
├── data/
│   └── processed/          # Datos limpios (parquet/feather) creados en el notebook
├── notebooks/
│   └── alurastore_analysis.ipynb  # Notebook principal con todo el flujo de trabajo
├── imgs/                   # Gráficos exportados por el notebook
│   ├── beneficio_por_tienda.png
│   ├── ingresos_anuales.png
│   ├── dispersion_costos_rating.png
│   └── mapa_calor_ventas.png
└── README
```

## 📊 Ejemplos de gráficos e insights
| Insight principal                                                                      |
| -------------------------------------------------------------------------------------- |
| **Tienda 1** encabeza el beneficio neto, pero con la calificación de clientes más baja |
| Crecimiento sostenido de **Tienda 2** entre 2021 y 2024                                |
| **Tienda 3** logra el mejor equilibrio coste–satisfacción                              |
| Alta concentración de ventas en el corredor Bogotá–Medellín                            |

<details>
<summary>Hallazgos clave</summary>

* **Beneficio neto** – Tienda 1 > Tienda 2 > Tienda 3 > Tienda 4.
* **Calificación media** – Tienda 3 ligeramente por encima de Tienda 2.
* **Costo de envío** – Tienda 4 es la más eficiente logísticamente.
* **Patrones geográficos** – Las tiendas con mayor concentración urbana presentan ratings más altos.
* **Recomendación** – Vender en **Tienda 3** por su equilibrio entre rentabilidad, satisfacción y logística.

</details>


Link de Colab: https://drive.google.com/file/d/1cAI5_RQ2e_4qa7gZlNd9ZZ5xyeSmiyA5/view?usp=sharing
Link de codigo: https://github.com/MakaryV/ONE-Challenge-2/blob/main/AluraMK.ipynb

---

© 2025 – Makary Villa. Proyecto para el Challenge #1 de Data Science Latam de **Alura**.
