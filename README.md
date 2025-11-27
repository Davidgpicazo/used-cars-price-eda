# Análisis Exploratorio de Datos – Coches de Segunda Mano

## Descripción
Este proyecto realiza un análisis exploratorio (EDA) de un dataset de coches de segunda mano con el objetivo de comprender cómo influyen distintas características del vehículo en su precio. El estudio permite identificar patrones relevantes del mercado y evaluar si los datos son adecuados para desarrollar un modelo predictivo que estime el precio de un coche dentro de una aplicación o plataforma de compra–venta.

## Objetivos del análisis
- Explorar las variables principales del dataset.
- Identificar relaciones que expliquen variaciones en el precio.
- Detectar anomalías y distribuciones relevantes.
- Evaluar las características más útiles para un modelo de predicción.

## Componentes del EDA
El análisis incluye las siguientes visualizaciones y métricas:

1. **Número de coches anunciados por marca**  
   Permite conocer qué marcas dominan la oferta disponible.

2. **Distribución del precio por marca**  
   Identifica diferencias entre marcas económicas, medias y premium.

3. **Relación entre precio y año de fabricación**  
   Analiza la depreciación del vehículo según su antigüedad.

4. **Relación entre precio y kilometraje**  
   Evalúa cómo afecta el uso del coche a su valor.

5. **Precio según número de propietarios**  
   Mide el impacto del historial del vehículo en su precio final.

6. **Matriz de correlación**  
   Revisa la relación entre las variables numéricas para detectar dependencias.

## Conclusiones principales
- La **marca** es un factor destacado para diferenciar rangos de precios.
- Los coches más recientes presentan precios significativamente más altos.
- Existe una relación inversa clara entre **kilometraje** y precio.
- Los coches con **menos propietarios** mantienen mejor su valor.
- El dataset presenta patrones estables que permiten plantear un **modelo predictivo fiable**.

## Tecnologías utilizadas
- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- Jupyter Notebook

## Próximos pasos
- Construcción de un modelo predictivo (p. ej. Random Forest o Gradient Boosting).
- Evaluación del rendimiento del modelo.
- Integración del estimador de precios en una aplicación o plataforma.

