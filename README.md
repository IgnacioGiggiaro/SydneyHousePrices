# SydneyHousePrices
# 🏠 Proyecto de Análisis Inmobiliario (EDA)

Un análisis exploratorio de datos (EDA) realizado con Python y Pandas sobre un conjunto de datos de ventas de propiedades. El objetivo de este proyecto es extraer insights clave sobre precios, ubicaciones y características de las propiedades en el mercado.

---

## 🚀 Objetivos del Análisis

Este proyecto responde a un conjunto de preguntas específicas de negocio para entender la composición del dataset:

1.  **Extremos de Precios:** Identificar la propiedad más cara y la más barata.
2.  **Ubicación de Extremos:** Determinar el barrio (`suburb`) de dichas propiedades.
3.  **Características Clave:** Contar los baños (`bath`) de esas dos propiedades.
4.  **Top Suburbs:** Encontrar el barrio con el precio de venta (`sellPrice`) promedio más elevado.
5.  **Tipo de Propiedad (Precio):** Identificar el tipo de propiedad (`propType`) con el precio promedio más bajo.
6.  **Filtro Específico:** Contar el número de "townhouse" en el código postal (`postalCode`) 2107.
7.  **Función de Agregación:** Implementar una función que calcule el precio promedio para una lista de tipos de propiedad, validando la entrada para asegurar que los tipos existan en el dataset.

---

## 📊 El Dataset

El conjunto de datos utilizado (asumiendo que se llama `datos.csv`) tiene la siguiente estructura:

| Columna | Tipo | Descripción |
| :--- | :--- | :--- |
| **Id** | `int` | Identificador único de la propiedad. |
| **Date** | `object` | Fecha de publicación o venta. |
| **suburb** | `object` | Barrio de la propiedad. |
| **postalCode**| `int` | Código postal. |
| **sellPrice** | `float` / `int` | Precio final de venta. |
| **bed** | `float` / `int` | Cantidad de habitaciones. |
| **bath** | `float` / `int` | Cantidad de baños. |
| **car** | `float` / `int` | Cantidad de espacios de estacionamiento. |
| **propType** | `object` | Tipo de propiedad (ej: 'house', 'unit'). |

---

## 🛠️ Tecnologías Utilizadas

* **Python 3.x**
* **Pandas:** Para la manipulación y análisis de datos.
* **Jupyter Notebook:** Para la ejecución interactiva del análisis.
