# Analisis de Ventas en UK

## Descripción:
Este proyecto analiza los datos de ventas minoristas realizadas con sede en UK, con el objetivo de identificar 


## Tabla de Contenidos 
- [Descripción](#descripción)
- [Datos](#datos)
- [Metodología](#metodología)
- [Resultados](#resultados)
- [Conclusión](#conclusión)

## Datos 
El dataset utilizado proviene de ventas minoristas en el Reino Unido y contiene múltiples columnas sobre transacciones de productos. 

## Metodología 

### Exploración de Datos 
- Exploración inicial del dataset para entender su estructura y contenido.
- Identificación de valores faltantes y atípicos.

### Limpieza de Datos 
- Eliminación de registros duplicados y valores nulos.
- Transformación de columnas para mejorar la calidad del dataset.

### Reducción de Dimensionalidad 
- Creación de una nueva columna llamada "Total", calculada como la multiplicación de la cantidad comprada por el precio unitario del producto.
- Construcción de un nuevo DataFrame con las siguientes columnas:
- - **Customer ID**: Identificación del cliente.
- - **Monetary Value**: Suma del total de compras pertenecientes al ID. 
- - **Frequency**: Número de facturas únicas del cliente.
- - **Recency**: Días desde la última compra.

### Normalización de Datos 
- Aplicación de la técnica de estandarización para normalizar las variables.

### Implementación de Algoritmo KMeans 
- Utilización del algoritmo KMeans para agrupar a los clientes en diferentes clusters.

### Análisis de los Grupos 
- Interpretación de los clusters creados para clasificar a los diferentes clientes y entender su comportamiento de compra.

## Resultados 
- Identificación de patrones en el comportamiento de compra de los clientes.
- Clasificación de clientes en diferentes grupos según su valor monetario, frecuencia de compra y recencia. ## Conclusión El análisis de datos permitió clasificar a los clientes en grupos distintos, lo cual puede ayudar a diseñar estrategias de marketing más efectivas y personalizadas.

## Conclusión 
El análisis de datos permitió clasificar a los clientes en grupos distintos, lo cual puede ayudar a diseñar estrategias de marketing más efectivas y personalizadas.  
  
**Autores:**
  - James Kevin Estrella Vilca - Estudiante - [JamesKevinStar](https://github.com/JamesKevinStar)
