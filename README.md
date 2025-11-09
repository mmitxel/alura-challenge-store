# 🏬 Challenge Alura Store

Desafío de **Data Science** del programa **ONE (Oracle Next Education)** de **Alura Latam**.

---

## 🎯 Objetivo

Poner en práctica conceptos iniciales de análisis de datos con **Python**, utilizando bibliotecas nativas para la manipulación, extracción y visualización de datos.

---

## 🧩 El desafío

Ayudar al **Sr. Juan** a decidir **qué tienda de su cadena Alura Store debe vender** para iniciar un nuevo emprendimiento.  
Para ello, se requiere analizar datos de ventas, rendimiento y reseñas de las **4 tiendas** de Alura Store.  

El objetivo es identificar la tienda menos eficiente y presentar una **recomendación final basada en los datos**.

---

## ⚙️ Procedimiento

1. Se utiliza lo aprendido en el curso de Data Science para revisar la estructura de los datos disponibles y extraer los necesarios mediante la librería **Pandas**.  
2. Se organizan los datos de forma que puedan ser manipulados fácilmente.  
3. Se grafican los valores y métricas obtenidas de la forma más adecuada para su comprensión, procurando **claridad visual**.  
4. Se realiza un análisis detallado comparando métricas **cuantitativas** (ventas, costos, calificaciones) y **cualitativas** (categorías de producto).  
5. Se obtienen conclusiones directamente derivadas de los datos mostrados y se presentan en un **informe final**.

---

## 🧠 Herramientas utilizadas

- **Google Colab (Jupyter Notebooks)**
- **Python**
  - Pandas  
  - Matplotlib
- **Trello**

---

## 💪 Habilidades reforzadas

- Importación, exploración de datos  
- Manipulación y análisis de datos
- Storytelling en datos
- Visualización clara y efectiva de información  

---

## 📊 Informe Final

Se realizó un análisis de las métricas en las cuatro tiendas para encontrar cuál de ellas sería más conveniente vender.  
Se analizaron tanto las variables de ventas y satisfacción de clientes, como aquellas que impactan estrategias comerciales.

Se descubrió que la **Tienda 4** muestra una clara **desventaja** respecto a las demás, por su **menor rentabilidad**, a pesar de contar con ventajas estratégicas:

#### 🔍 Descubrimientos Clave
- La tienda #4 genera un **6 a 11% menos ingresos** que las otras, a pesar de tener menores costos de envío.
- Sus categorías de productos más vendidos difieren, lo cual complica las estrategias de marketing unificadas.
- Todas las tiendas tienen similar satisfacción de clientes (~4.0/5).
- **Recomendaci+on:** Vender la Tienda #4.

### 📋 Análisis

### 🔹 Facturación total

Su **facturación** es significativamente menor que la de las otras tiendas:  
solo **1 308.4 millones de COP**, contra **1 150.9**, **1 116.3** y **1 098.0 millones de COP** de las demás _(Figura 1)_.  
Esto representa una diferencia que va del **6 % al 11 %** _(Figura 2)_.

### 🔹 Costos de envío

Se encontró que la Tienda 4 tiene **costos de envío más bajos** que las demás _(Figura 3)_,  
aunque esto **no se ha reflejado en mayores ventas**, como podría esperarse.

### 🔹 Categorías de productos

Las tiendas **3 y 4** muestran distribuciones diferentes respecto a las 1 y 2:  
- En la **Tienda 3**, las ventas de **libros** superan a las de **instrumentos musicales**.  
- En la **Tienda 4**, las de **artículos para el hogar** superan a ambas categorías,  
  y las de **deportes y diversión** incluso superan a **electrodomésticos**,  
  algo que no ocurre en las demás _(Figura 4)_.  

Esto sugiere que cualquier estrategia de marketing (descuentos, promociones, campañas) deberá considerar las diferencias de la Tienda 4, lo que **podría complicar su implementación y reducir su efectividad**.

### 🔹 Calificación de los clientes

Las calificaciones promedio no muestran diferencias significativas:  
todas las tiendas se encuentran **entre 3.98 y 4.05** _(Figura 5)_,  
por lo que este factor **no influye** en la decisión.

---

### 🧾 Conclusión

> Se recomienda la **venta de la Tienda 4**  
> debido a su **menor rentabilidad y desventaja competitiva**.

---

## 📈 Figuras

<p align="center">
  <img src="https://github.com/user-attachments/assets/7973bfaf-d07a-4298-b9b4-b88fe8069e89" width="720">
</p>
<p align="center"><em>Figura 1. Facturación total por tienda</em></p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/8ecd73b5-d765-46ec-bef2-b21962efd1aa" width="720">
</p>
<p align="center"><em>Figura 2. Diferencia relativa de facturación</em></p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/90d300ec-5e91-4d67-b970-5e13737a9c9d" width="720">
</p>
<p align="center"><em>Figura 3. Costos de envío promedio por tienda</em></p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/170095e5-dd08-4293-86fd-01e7e025020c" width="900">
</p>
<p align="center"><em>Figura 4. Distribución de ventas por categoría y tienda</em></p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/2c640f91-e1bd-401d-8b34-6decae094457" width="520">
</p>
<p align="center"><em>Figura 5. Calificación promedio de las tiendas</em></p>

---

📘 _Análisis elaborado como parte del programa **Alura ONE - Data Science**._  
