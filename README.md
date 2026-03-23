# Práctica IA (RA4 · f)

## 1) Caso de uso
- Tipo de aplicación: Aplicación web de recomendación de productos (e-commerce)
- Problema: Los usuarios tienen dificultades para encontrar productos relevantes entre miles de opciones, lo que reduce la conversión y la satisfacción.
- Usuario: Clientes de la tienda online que buscan productos adaptados a sus intereses.

## 2) Datos
- Datos:
  - Historial de compras
  - Productos vistos
  - Valoraciones (ratings)
  - Datos de navegación (clics, tiempo en página)
  - Información básica del usuario (edad, preferencias, etc.)
- Tipo minería: Minería de datos predictiva (machine learning supervisado y sistemas de recomendación)

## 3) Pipeline
- Recogida:
  - Captura de datos desde la web (cookies, logs, formularios)
  - Almacenamiento en base de datos (SQL/NoSQL)

- Limpieza:
  - Eliminación de datos duplicados
  - Tratamiento de valores nulos
  - Filtrado de datos irrelevantes o erróneos

- Transformación:
  - Normalización de datos
  - Codificación de variables (ej: one-hot encoding)
  - Generación de features (ej: frecuencia de compra, categorías favoritas)

- Entrenamiento:
  - Uso de algoritmos de recomendación (ej: filtrado colaborativo, modelos de clasificación)
  - División de datos en entrenamiento/test
  - Ajuste de parámetros del modelo

- Predicción:
  - Generación de recomendaciones personalizadas para cada usuario
  - Ranking de productos según probabilidad de interés

- Uso:
  - Integración en la aplicación web (frontend/backend)
  - Mostrar recomendaciones en tiempo real (ej: “Productos recomendados para ti”)
  - Mejora de la experiencia de usuario y aumento de ventas
