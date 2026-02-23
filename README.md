# Práctica IA (RA4 · a) — Automatización y optimización

## 1) Proceso elegido
- **Nombre del proceso**: Soporte al cliente en atención a través de chatbots.
- **Contexto (empresa/servicio web/IT)**: Servicio web de atención al cliente en una empresa de e-commerce.
- **Rol/es implicados**: Agentes de atención al cliente, equipo de TI, equipo de gestión de la experiencia del cliente (CX).

## 2) ANTES (sin IA)
- **Pasos (5–7)**:
  1. El cliente ingresa a la web y selecciona la opción de "Atención al cliente".
  2. El cliente selecciona un tema de consulta (envío, devolución, información de producto, etc.).
  3. Un agente humano recibe la consulta y responde según el tema indicado, generalmente a través de chat en vivo.
  4. El agente puede requerir más información o proceder con la solución manual (como actualizar el estado de un pedido o enviar un correo con instrucciones adicionales).
  5. El cliente recibe la respuesta tras un tiempo de espera que depende de la disponibilidad de agentes.

- **Tiempo aproximado por caso**: 10–15 minutos por consulta, dependiendo de la complejidad del problema.

- **Problemas / cuellos de botella**:
  - Respuesta lenta en horarios de alta demanda.
  - Posible repetición de consultas comunes que ocupan mucho tiempo de los agentes.
  - Limitada disponibilidad de agentes durante ciertas horas.
  - Posible inconsistencia en las respuestas debido a diferentes niveles de experiencia de los agentes.

## 3) DESPUÉS (con IA)
- **¿Qué automatiza la IA?**
  La IA automatiza la clasificación de consultas y la respuesta automática a preguntas frecuentes mediante un chatbot inteligente. El bot también puede guiar al usuario para resolver problemas sencillos o realizar tareas automáticas como reembolsos y cambios de pedidos.

- **¿Qué queda para humanos?**
  Los humanos siguen encargándose de casos complejos que no pueden ser resueltos automáticamente por la IA, o que requieren interacción personal (por ejemplo, reclamaciones especiales, atención personalizada en casos de problemas graves).

- **Datos necesarios (tipos de datos, sin datos personales)**:
  - Información de productos (descripciones, stock, precios).
  - Historial de interacciones anteriores de los clientes con la empresa.
  - Datos de seguimiento de pedidos (estado del envío, fecha de entrega estimada).
  - Preguntas frecuentes y soluciones predefinidas.

- **Modelo/técnica (NLP, clasificación, recomendación, visión, etc.)**:
  - **NLP (Procesamiento de Lenguaje Natural)**: para interpretar y comprender las consultas del cliente.
  - **Clasificación de texto**: para dirigir las consultas a las categorías correctas.
  - **Recomendación**: para sugerir productos o acciones automáticas basadas en la consulta del usuario.

## 4) Optimización (mejora medible)
Define 3 métricas con valores antes/después:

- **Tiempo**:
  - **Antes**: 10–15 minutos por consulta.
  - **Después**: 2–3 minutos por consulta (resolución instantánea o derivación correcta al agente).

- **Coste**:
  - **Antes**: Requiere mantener un equipo de agentes para cubrir turnos de atención 24/7.
  - **Después**: Reducción del coste operativo al automatizar un 60–70% de las consultas, permitiendo que los agentes se centren en los casos más complejos.

- **Calidad**:
  - **Antes**: Variabilidad en la calidad de la atención, dependiendo de la experiencia de los agentes.
  - **Después**: Respuestas más consistentes y precisas debido a la automatización, con un 90% de precisión en respuestas básicas por parte del chatbot.

## 5) Diagrama del flujo (ASCII o Mermaid)

mermaid
graph TD
    A[Cliente inicia sesión] --> B[Selecciona tipo de consulta]
    B --> C{Consulta común?}
    C -->|Sí| D[Bot responde automáticamente]
    C -->|No| E[Bot transfiere a agente]
    D --> F[Cliente recibe respuesta]
    E --> F[Agente humano responde]
    F --> G[Consulta resuelta]

## 6) Riesgos y mitigación
- **Riesgo 1**: La IA no puede resolver todos los casos complejos, lo que podría generar frustración en los usuarios si el chatbot no redirige correctamente.
  - **Mitigación 1**: Entrenar constantemente al chatbot con nuevas interacciones y feedback de los usuarios, y crear un proceso claro para la transferencia a agentes humanos en caso de problemas complejos.
  
- **Riesgo 2**: Posible falta de confianza en la IA por parte de los usuarios, especialmente si sienten que la máquina no entiende correctamente sus necesidades.
  - **Mitigación 2**: Implementar un sistema de aclaración donde los clientes puedan fácilmente contactar a un humano si lo desean, además de usar un tono amigable y transparente en las respuestas del bot.

## 7) Fuente oficial
- [IBM Watson Assistant - Implementación de chatbots](https://www.ibm.com/cloud/watson-assistant)
