# Práctica IA (RA4 · d+e) — Sectores con implantación relevante y lenguajes de programación en IA

## 1) Introducción

**Objetivo de la práctica:**  
El objetivo de esta práctica es analizar tres sectores donde la Inteligencia Artificial (IA) tiene una implantación relevante. Se estudiará qué aplicaciones de IA se utilizan en cada sector, qué problemas ayudan a resolver, qué beneficios aportan a las empresas o usuarios y qué lenguajes de programación se utilizan habitualmente para desarrollar estas soluciones.

**Relación con DAW/DAM:**  
Esta práctica se relaciona con los ciclos formativos de Desarrollo de Aplicaciones Web (DAW) y Desarrollo de Aplicaciones Multiplataforma (DAM), ya que muchas aplicaciones actuales integran servicios de Inteligencia Artificial. Los desarrolladores pueden utilizar APIs de IA, bibliotecas de machine learning o servicios en la nube para crear aplicaciones más inteligentes, como sistemas de recomendación, chatbots o herramientas de análisis de datos.

---

## 2) Sectores con implantación relevante de IA

### Sector 1
- **Nombre del sector:** Sanidad (Healthcare)
- **Tipo de empresa/servicio:** Hospitales, clínicas, centros de investigación médica y empresas de tecnología sanitaria.
- **Aplicación de IA:** Sistemas de diagnóstico asistido mediante análisis de imágenes médicas.
- **Qué tarea mejora o automatiza:** Analiza radiografías, resonancias o TAC para detectar enfermedades o anomalías de forma más rápida.
- **Por qué la IA tiene implantación relevante en este sector:** El sector sanitario genera una gran cantidad de datos médicos que pueden analizarse con IA para ayudar en el diagnóstico y en la toma de decisiones médicas.
- **Beneficios que aporta:**
  - Diagnósticos más rápidos.
  - Mayor precisión en la detección de enfermedades.
  - Reducción de errores humanos.
  - Apoyo a los profesionales sanitarios.
- **Lenguajes de programación habituales:**
  - Python
  - R
  - Java
  - C++

---

### Sector 2
- **Nombre del sector:** Comercio electrónico (E-commerce)
- **Tipo de empresa/servicio:** Tiendas online, marketplaces y plataformas de venta digital.
- **Aplicación de IA:** Sistemas de recomendación de productos.
- **Qué tarea mejora o automatiza:** Analiza el comportamiento del usuario (compras, búsquedas, clics) para recomendar productos personalizados.
- **Por qué la IA tiene implantación relevante en este sector:** Las plataformas de comercio electrónico manejan grandes cantidades de datos de clientes y productos que pueden utilizarse para mejorar la experiencia de compra.
- **Beneficios que aporta:**
  - Experiencia personalizada para el usuario.
  - Aumento de ventas.
  - Mayor fidelización de clientes.
  - Mejora de estrategias de marketing.
- **Lenguajes de programación habituales:**
  - Python
  - JavaScript
  - Java
  - Scala

---

### Sector 3
- **Nombre del sector:** Transporte y movilidad
- **Tipo de empresa/servicio:** Empresas de transporte, logística, reparto y desarrollo de vehículos autónomos.
- **Aplicación de IA:** Sistemas de conducción autónoma y optimización de rutas.
- **Qué tarea mejora o automatiza:** Analiza datos de tráfico, sensores y mapas para tomar decisiones de conducción o calcular rutas más eficientes.
- **Por qué la IA tiene implantación relevante en este sector:** El transporte requiere analizar datos en tiempo real para mejorar la seguridad y la eficiencia de los desplazamientos.
- **Beneficios que aporta:**
  - Reducción de accidentes.
  - Optimización de rutas.
  - Ahorro de tiempo y combustible.
  - Mejora de la logística.
- **Lenguajes de programación habituales:**
  - Python
  - C++
  - Java
  - MATLAB

---

## 3) Lenguajes de programación en IA

### Lenguaje 1
- **Nombre:** Python
- **Uso principal en IA:** Desarrollo de modelos de machine learning, análisis de datos y redes neuronales.
- **Ventajas:**
  - Sintaxis sencilla y fácil de aprender.
  - Gran cantidad de librerías especializadas (TensorFlow, PyTorch, Scikit-learn).
  - Amplia comunidad y documentación.
- **Ejemplos de uso:**
  - Sistemas de recomendación en comercio electrónico.
  - Análisis de imágenes médicas en sanidad.
  - Desarrollo de modelos de predicción.

---

### Lenguaje 2
- **Nombre:** R
- **Uso principal en IA:** Análisis estadístico, procesamiento de datos y creación de modelos predictivos.
- **Ventajas:**
  - Muy potente para análisis estadístico.
  - Gran cantidad de paquetes para análisis de datos.
  - Muy utilizado en investigación y ciencia de datos.
- **Ejemplos de uso:**
  - Análisis de datos médicos.
  - Modelos estadísticos para investigación.
  - Visualización de datos complejos.

---

### Lenguaje 3
- **Nombre:** Java
- **Uso principal en IA:** Desarrollo de aplicaciones empresariales que integran modelos de inteligencia artificial.
- **Ventajas:**
  - Muy utilizado en sistemas grandes y escalables.
  - Buena integración con aplicaciones backend.
  - Gran estabilidad y rendimiento.
- **Ejemplos de uso:**
  - Sistemas de recomendación en plataformas de comercio electrónico.
  - Aplicaciones empresariales con análisis de datos.
  - Sistemas de gestión logística.

---

### Lenguaje 4
- **Nombre:** C++
- **Uso principal en IA:** Desarrollo de sistemas de alto rendimiento y procesamiento en tiempo real.
- **Ventajas:**
  - Muy rápido y eficiente.
  - Permite un control detallado del hardware.
  - Ideal para sistemas que requieren gran rendimiento.
- **Ejemplos de uso:**
  - Software para conducción autónoma.
  - Procesamiento de imágenes.
  - Sistemas de visión artificial.

---

## 4) Relación entre sectores, tipo de IA y lenguaje

| Sector | Aplicación de IA | Tipo de IA/técnica | Lenguaje recomendado | Justificación |
|--------|------------------|--------------------|----------------------|---------------|
| Sanidad | Diagnóstico mediante imágenes médicas | Visión artificial y aprendizaje profundo | Python | Tiene muchas librerías especializadas en machine learning y análisis de imágenes. |
| Comercio electrónico | Sistemas de recomendación de productos | Machine Learning y análisis de datos | Python / Java | Python para desarrollar los modelos y Java para integrarlos en plataformas web grandes. |
| Transporte y movilidad | Conducción autónoma y optimización de rutas | Visión artificial y aprendizaje automático | C++ / Python | C++ se utiliza para sistemas en tiempo real y Python para el desarrollo de modelos de IA. |

---

## 5) Diagrama (ASCII o Mermaid)

```mermaid
graph TD

A[Inteligencia Artificial] --> B[Sanidad]
A --> C[Comercio electrónico]
A --> D[Transporte y movilidad]

B --> B1[Diagnóstico con imágenes]
B1 --> B2[Python]

C --> C1[Sistemas de recomendación]
C1 --> C2[Python / Java]

D --> D1[Conducción autónoma]
D1 --> D2[C++ / Python]
