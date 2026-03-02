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

## 4) IA aplicada: modelo y decisión

- **Tipo de IA/técnica:**  
Sistemas de recomendación (machine learning supervisado) + modelos predictivos de demanda.

- **Entrada del modelo (qué datos usa):**  
Datos de navegación (clics, búsquedas, tiempo en página), historial de compras, productos añadidos al carrito, frecuencia de compra, ubicación del cliente y datos históricos de ventas.

- **Salida del modelo (qué produce):**  
- Lista personalizada de productos recomendados.  
- Predicción de demanda por producto y zona geográfica.  
- Probabilidad de que un usuario compre un producto concreto.

- **Decisión que habilita (qué hace la empresa con esa salida):**  
- Mostrar recomendaciones personalizadas en la página principal y en cada producto.  
- Ajustar inventario en almacenes según la demanda prevista.  
- Lanzar promociones personalizadas a clientes con alta probabilidad de compra.  

---

## 5) Rentabilidad: KPIs antes/después

### KPI 1 (Tasa de conversión – ingresos)
- **Antes:** 2,5% de los usuarios que visitan la web compraban.  
- **Después:** 3,5% tras implementar recomendaciones personalizadas.  
- **Por qué mejora la rentabilidad:**  
Más compradores por el mismo tráfico web significa mayor facturación sin aumentar proporcionalmente el gasto en publicidad.

---

### KPI 2 (Roturas de stock – eficiencia logística)
- **Antes:** 8% de productos con rotura de stock.  
- **Después:** 3% gracias a la predicción de demanda.  
- **Por qué mejora la rentabilidad:**  
Se reducen ventas perdidas y costes de urgencia en reposición.

---

### KPI 3 (Valor medio del pedido – ticket medio)
- **Antes:** 35 € por pedido.  
- **Después:** 42 € por pedido gracias al cross-selling automático.  
- **Por qué mejora la rentabilidad:**  
Cada cliente genera más ingresos por compra, aumentando el margen global.

---

## 6) Diagrama del pipeline (ASCII)

A[Usuarios (Web/App)] --> B[Captura de datos: clics, compras, búsquedas]
B --> C[Limpieza y normalización]
C --> D[Data Lake]
D --> E[Preparación de variables]
E --> F[Modelo de recomendación y predicción]
F --> G[Recomendaciones + Predicción de demanda]
G --> H[Decisiones: promociones, stock, precios]
H --> I[Impacto en ventas y reducción de costes]

## 7) Riesgos y mitigación

### Riesgo 1: Privacidad y protección de datos
- **Mitigación 1:** Implementar cifrado de datos sensibles, cumplir con GDPR y otras normativas de privacidad, y anonimizar los datos de los usuarios cuando se usan para entrenar modelos.

### Riesgo 2: Sesgos en los modelos de IA
- **Mitigación 2:** Realizar auditorías periódicas de los algoritmos, entrenar con datos diversos y balanceados, e implementar controles de equidad en las recomendaciones y predicciones.

---

## 8) Valoración (criterio c): importancia presente y futura de la IA

- **Importancia actual (hoy):**  
La IA permite a empresas como Amazon optimizar ventas, personalizar la experiencia del cliente y mejorar la eficiencia logística. Los sistemas de recomendación y predicción de demanda son claves para aumentar ingresos y reducir costes operativos.

- **Importancia futura (3–5 años):**  
Se espera que la IA evolucione hacia modelos más precisos, integración en tiempo real en todos los procesos de negocio, y automatización avanzada de logística y marketing personalizado. Las empresas que no adopten IA perderán competitividad.

- **Condiciones/limitaciones:**  
Se requiere calidad y volumen de datos suficiente, inversión en infraestructura y talento especializado, cumplimiento de regulaciones de privacidad y ética, y mitigación de impactos en empleo por automatización.

- **Conclusión razonada:**  
La IA es estratégica para la rentabilidad y sostenibilidad empresarial. Su implementación efectiva no solo incrementa ventas y eficiencia, sino que también permite una ventaja competitiva a largo plazo, siempre que se gestionen riesgos de privacidad, sesgo y costes.

---

## 9) Fuentes oficiales (mín. 2)

- **Big Data/analítica (enlace oficial):**  
[Amazon Big Data & Analytics Services](https://aws.amazon.com/big-data/)

- **IA/técnica/modelo (enlace oficial):**  
[Amazon Machine Learning & AI Services](https://aws.amazon.com/machine-learning/)
