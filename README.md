# 📊 Práctica IA (RA4 · b+c) — Big Data, análisis, rentabilidad y valoración IA

---

## 1) Caso y objetivo de negocio

### Empresa/sector (real):
Amazon (sector e-commerce)

### Problema a resolver:
Gestionar millones de productos y clientes en tiempo real, optimizando ventas y logística.

### Objetivo de negocio (rentabilidad):
- Aumentar ventas mediante recomendaciones personalizadas.
- Reducir costes logísticos con predicción de demanda.
- Minimizar fraude y devoluciones.

---

## 2) Big Data: recogida masiva de datos

Amazon es un caso claro de Big Data porque cumple las 3V:

- **Volumen**: millones de usuarios, productos y transacciones diarias.
- **Velocidad**: datos generados y procesados en tiempo real.
- **Variedad**: datos estructurados y no estructurados.

### Fuente 1:
Datos de navegación (clics, búsquedas, tiempo en página, carrito).

### Fuente 2:
Datos de transacciones (compras, devoluciones, métodos de pago).

### Fuente 3:
Datos logísticos (envíos, almacenes, tiempos de entrega).

### Volumen/velocidad (estimación):
Millones de eventos por hora a nivel global, procesados en tiempo real.

### Formatos:
Texto (reseñas), eventos digitales, series temporales (ventas), imágenes (productos), datos geográficos.

---

## 3) Tratamiento/análisis: pipeline de datos

### Ingesta (captura/eventos):
Recogida automática de datos desde la web, app móvil y sistemas logísticos.

### Limpieza/normalización:
Eliminación de duplicados, corrección de errores y estandarización de datos.

### Almacenamiento (data lake/warehouse):
Almacenamiento masivo en sistemas distribuidos que permiten análisis a gran escala.

### Preparación de variables (features):
Creación de variables como historial de compra, frecuencia, productos vistos y ubicación.

### Análisis/BI (opcional):
Uso de modelos de IA para:
- Sistemas de recomendación.
- Predicción de demanda.
- Detección de fraude.
- Optimización de rutas.
