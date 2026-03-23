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

## 4) Integración
- Backend:
  - API REST desarrollada en Node.js / Java (Spring Boot)
  - Servicio de IA separado (microservicio) que contiene el modelo entrenado
  - Conexión con base de datos para consultar usuarios, productos y resultados
  - Endpoint para obtener recomendaciones personalizadas

- Frontend:
  - Aplicación web (React / Angular / Vue)
  - Consumo de la API mediante fetch/AJAX
  - Visualización de recomendaciones en secciones como “Productos para ti”
  - Interacción del usuario (clics, compras) que se envían de vuelta al backend

- Flujo:
  1. El usuario entra en la web
  2. El frontend solicita recomendaciones al backend
  3. El backend envía datos del usuario al modelo de IA
  4. El modelo genera predicciones (productos recomendados)
  5. El backend devuelve los resultados al frontend
  6. El frontend muestra los productos al usuario
  7. Las nuevas interacciones se guardan para mejorar el modelo

## 5) Valor
- Mejora:
  - Personalización de la experiencia de usuario
  - Aumento del tiempo de permanencia en la web
  - Incremento de la tasa de conversión (más compras)

- Sin IA:
  - Recomendaciones genéricas (productos más vendidos o aleatorios)
  - Menor relevancia para el usuario
  - Peor experiencia y menor fidelización

- Rentabilidad:
  - Incremento de ventas por recomendaciones acertadas
  - Mejora del engagement del usuario
  - Optimización del marketing (menos gasto en publicidad innecesaria)

## 6) Diagrama 
Usuario
   │
   ▼
Frontend (Web)
   │
   ▼
Backend (API REST)
   │
   ▼
Modelo de IA (Recomendador)
   │
   ▼
Base de Datos
   │
   ▲
Resultados (Recomendaciones)
   │
   ▲
Frontend muestra productos

## 7) Riesgos
- Riesgo 1: Predicciones inexactas debido a datos incompletos o sesgados  
- Mitigación 1: Revisar y limpiar los datos, aplicar técnicas de balanceo y validación cruzada

- Riesgo 2: Vulnerabilidad de datos personales de usuarios  
- Mitigación 2: Implementar cifrado, políticas de privacidad, anonimización de datos y cumplimiento de GDPR/LOPD

## 8) Fuente
- Documentación oficial de frameworks de IA y minería de datos (Scikit-learn, TensorFlow, PyTorch)  
- Artículos sobre sistemas de recomendación en e-commerce (Medium, Towards Data Science)  
- Experiencias de integración de IA en aplicaciones web (blogs y casos prácticos DAW/DAM)
