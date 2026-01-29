# 🛒 Alura Store – Análisis de Datos

## 📌 Propósito del proyecto

Este proyecto tiene como objetivo analizar los datos de ventas de la **Alura Store**, consolidando la información de cuatro tiendas distintas para obtener insights clave sobre el desempeño del negocio.

A través del análisis se busca:

* Calcular la **facturación total** de la tienda.
* Identificar las **categorías de productos más vendidas**.
* Analizar la **calificación promedio** de las tiendas.
* Detectar los **productos más y menos vendidos**.
* Evaluar el **costo promedio de envío por tienda**.

El análisis se realizó utilizando **Python** y la librería **pandas**, aplicando conceptos básicos de análisis de datos.

---

## 📂 Estructura del proyecto

```text
alura-store/
│
├── data/
│   ├── tienda_1.csv
│   ├── tienda_2.csv
│   ├── tienda_3.csv
│   └── tienda_4.csv
│
├── notebooks/
│   └── alura_store_analisis.ipynb
│
├── README.md
```

### Descripción de los archivos

* **data/**: contiene los archivos CSV con las ventas de cada tienda.
* **notebooks/**: notebook principal donde se realiza todo el análisis.
* **README.md**: documentación del proyecto.

---

## 📊 Ejemplos de análisis, gráficos e insights

Durante el análisis se obtuvieron los siguientes resultados:

### 🔹 Facturación total

* La facturación total consolidada de las cuatro tiendas fue superior a **$4.600 millones**, lo que refleja un alto volumen de ventas.

### 🔹 Ventas por categoría

* Se identificaron categorías con mayor volumen de ventas, permitiendo reconocer cuáles productos concentran la mayor demanda.

*(Ejemplo de gráfico sugerido: gráfico de barras con ventas por categoría)*

### 🔹 Calificación promedio

* El promedio de calificaciones permitió evaluar la percepción de los clientes sobre cada tienda.

*(Ejemplo de gráfico sugerido: gráfico de barras con calificación promedio por tienda)*

### 🔹 Productos más y menos vendidos

* Se identificó el producto con mayor número de ventas y aquel con menor rotación, información clave para decisiones de stock y marketing.

### 🔹 Envío promedio por tienda

* El análisis del costo promedio de envío permitió comparar la eficiencia logística entre tiendas.

---

## ▶️ Instrucciones para ejecutar el notebook

1. Clonar este repositorio o descargar los archivos.
2. Asegurarse de tener **Python 3.9+** instalado.
3. Instalar las dependencias necesarias:

```bash
pip install pandas
```

4. Abrir el notebook:

```bash
jupyter notebook notebooks/alura_store_analisis.ipynb
```

5. Ejecutar las celdas en orden para reproducir el análisis.

---

## 🧠 Conclusión

Este proyecto permite aplicar de forma práctica conceptos fundamentales de análisis de datos, como limpieza, consolidación y exploración de información, entregando insights útiles para la toma de decisiones comerciales en un entorno de ventas reales.

📈 Proyecto desarrollado como parte del desafío **Data Science – Alura LATAM**.
