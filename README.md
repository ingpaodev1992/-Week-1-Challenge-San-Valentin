### **💖 Análisis del Amor en las Compras en Amazon 💖**  

#### **🛍️ Explorando los Productos Más Populares, Sus Precios y la Influencia de las Reseñas en las Decisiones de Compra 💬**  

Este dashboard analiza los productos más populares en Amazon, sus precios y cómo las reseñas influyen en las decisiones de compra. Se basa en un conjunto de datos obtenido de Kaggle, el cual fue sometido a un exhaustivo proceso de limpieza para garantizar datos confiables y bien estructurados.  

### **🧹 Limpieza y Transformación de Datos**  

Antes de construir las visualizaciones, se realizaron varias tareas clave para preparar el dataset:  

- **🗑️ Eliminación de valores nulos** para evitar inconsistencias en el análisis.  
- **🔄 Despivoteo de columnas**, reestructurando los datos para una mejor visualización.  
- **📊 Cálculo de promedios** para precios y reseñas, permitiendo completar datos faltantes de manera precisa.  
- **🔢 Conversión de datos categóricos a valores numéricos**, transformando la columna *Estrellas* en *Número de Estrellas* para un análisis más sencillo.  

Además, se crearon **cuatro segmentadores** para filtrar los datos por:  
1. **Categoría** (🛒)  
2. **Marca** (🏷️)  
3. **Precio en USD** (💰)  
4. **Número de Estrellas** (⭐)  

### **📊 Visualizaciones y Análisis**  

1️⃣ **Treemap: Total de Reseñas por Tipo de Producto**  
   - Este gráfico representa el **número total de reseñas** recibidas por cada tipo de producto.  
   - Las categorías con más reseñas son **Tarjetas de Regalo 🎁, Chocolates 🍫, Kits de Cuidado Personal 🧴 y Joyería 💎**.  
   - Las categorías con menos reseñas aparecen en secciones más pequeñas, facilitando la identificación de los productos con mayor interacción de los clientes.  

2️⃣ **Gráfico de Barras Apiladas: ¿Qué Categorías Tienen los Productos Más Costosos?**  
   - Esta visualización muestra el **precio promedio de los productos** dentro de cada categoría.  
   - Ayuda a identificar qué tipos de productos son **más caros** en comparación con otros.  
   - Permite una comparación clara y una mejor comprensión de la distribución de precios en las distintas categorías.  

3️⃣ **Matriz: Distribución de Reseñas por Categoría y Calificación**  
   - Esta tabla muestra de manera estructurada las **categorías de productos en la primera columna**, seguidas por el número de reseñas con **3, 4 o 5 estrellas**.  
   - Una columna adicional muestra el **total de votos por categoría**, facilitando la comparación de la distribución de reseñas.  
   - Al ordenar la tabla de forma descendente, se destacan las categorías con el mayor número de calificaciones.  

4️⃣ **Gráfico de Dispersión: Relación entre el Precio y las Reseñas por Calificación**  
   - Este gráfico analiza la **relación entre el precio del producto y el número de reseñas**, diferenciando entre **calificaciones de 3, 4 y 5 estrellas**.  
   - Muestra claramente que **los productos más caros no son necesariamente los mejor calificados**.  
   - La mayoría de los productos con un alto número de reseñas se encuentran en el **rango de precio de $0 a $50**, lo que sugiere que los consumidores tienden a dejar más reseñas en productos asequibles.  

### **❤️ Conclusiones Clave**  
- **Las Tarjetas de Regalo y los Chocolates dominan en popularidad**, obteniendo el mayor número de reseñas.  
- **El precio no determina directamente la cantidad de reseñas ni la calificación promedio**, lo que indica que factores como la calidad y el marketing tienen un impacto más significativo en las decisiones de compra.  
- **La matriz permite visualizar cómo se distribuyen las calificaciones entre diferentes categorías**, facilitando la identificación de los productos con mayor retroalimentación en distintos niveles de estrellas.  

Este dashboard ofrece una **visión clara y estructurada** del comportamiento de compra en Amazon, brindando información sobre la relación entre **precios, reseñas y popularidad de los productos**. ¡Feliz análisis! 💕📊  

Dataset obtenido de Kaggle https://www.kaggle.com/datasets/kanchana1990/2024-amazon-best-sellers-top-valentine-gifts 
Link a mi dashboard de Power BI publicado  https://app.powerbi.com/links/yV0g1nm4dg?ctid=b1ba85eb-a253-4467-9ee8-d4f8ed4df300&pbi_source=linkShare
