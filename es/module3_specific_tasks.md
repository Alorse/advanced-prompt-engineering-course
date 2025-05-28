# Módulo 3: Prompting para Tareas Específicas de Ingeniería de Software

## Objetivo del Módulo
Aplicar técnicas de prompt engineering a tareas concretas y cotidianas de ingeniería de software, optimizando la interacción con LLMs para maximizar su utilidad en el flujo de trabajo de desarrollo.

## Lecciones

### Lección 3.1: Generación y Optimización de Código
**Descripción:** Técnicas específicas para obtener código de alta calidad, mantenible y eficiente a partir de LLMs.

**Contenido:**
- Especificación precisa de requisitos funcionales y no funcionales
- Técnicas para solicitar diferentes implementaciones alternativas
- Prompts para optimización de rendimiento, seguridad y legibilidad
- Estrategias para generación de código en lenguajes específicos

**Ejercicio Práctico:** 
Desarrollar una serie de prompts progresivos para generar una API REST completa, desde la especificación inicial hasta la implementación optimizada. Utilizar OpenAI API con diferentes parámetros de temperatura para comparar la calidad y creatividad del código generado.

### Lección 3.2: Explicación y Comprensión de Código Complejo
**Descripción:** Métodos para utilizar LLMs como herramientas de comprensión y documentación de código existente.

**Contenido:**
- Estructuración de prompts para análisis de código por componentes
- Técnicas para solicitar explicaciones a diferentes niveles de abstracción
- Prompts para identificación de patrones de diseño y arquitectura
- Métodos para generar documentación a partir de código

**Ejercicio Práctico:** 
Seleccionar un fragmento de código complejo (por ejemplo, un algoritmo de machine learning) y diseñar prompts que generen explicaciones a tres niveles: visión general, flujo lógico detallado y análisis línea por línea. Implementar en Claude y evaluar la precisión y claridad de las explicaciones.

### Lección 3.3: Traducción de Código Entre Lenguajes
**Descripción:** Técnicas para obtener traducciones precisas y idiomáticas de código entre diferentes lenguajes de programación.

**Contenido:**
- Especificación de convenciones y estilo del lenguaje destino
- Manejo de diferencias fundamentales entre paradigmas de programación
- Preservación de comentarios y documentación durante la traducción
- Verificación de equivalencia funcional

**Ejercicio Práctico:** 
Crear prompts para traducir una clase Java con patrones de diseño complejos a Python, manteniendo la funcionalidad y adaptándose a las convenciones de Python. Implementar en Gemini y evaluar la calidad de la traducción según criterios predefinidos.

### Lección 3.4: Generación de Pruebas Unitarias y de Integración
**Descripción:** Metodologías para utilizar LLMs en la creación de suites de pruebas completas y robustas.

**Contenido:**
- Especificación de cobertura y tipos de pruebas deseadas
- Prompts para generación de casos de prueba exhaustivos
- Técnicas para pruebas de casos límite y manejo de errores
- Integración con frameworks de testing específicos

**Ejercicio Práctico:** 
Diseñar prompts para generar pruebas unitarias completas para un módulo de autenticación, incluyendo casos felices, casos límite y manejo de errores. Implementar en ChatGPT y evaluar la cobertura y robustez de las pruebas generadas.

### Lección 3.5: Creación de Documentación Técnica y Diagramas
**Descripción:** Técnicas para generar documentación clara, completa y útil para diferentes audiencias técnicas.

**Contenido:**
- Prompts para diferentes tipos de documentación (API, arquitectura, usuario)
- Especificación de nivel de detalle y audiencia objetivo
- Generación de descripciones para diagramas técnicos
- Estructuración de documentación técnica compleja

**Ejercicio Práctico:** 
Crear prompts para generar documentación completa de una API REST, incluyendo descripción de endpoints, parámetros, respuestas y ejemplos de uso. Utilizar la API de OpenAI para generar la documentación en formato Markdown y evaluar su claridad y completitud.

### Lección 3.6: Debugging Asistido por IA
**Descripción:** Metodologías para aprovechar los LLMs en la identificación, análisis y resolución de bugs.

**Contenido:**
- Estructuración de la información del error para análisis efectivo
- Técnicas de razonamiento paso a paso para debugging
- Prompts para generación de hipótesis y planes de prueba
- Verificación y validación de soluciones propuestas

**Ejercicio Práctico:** 
Desarrollar una metodología de prompting para analizar un stack trace y código relacionado, identificar posibles causas del error y proponer soluciones verificables. Implementar en Claude y documentar el proceso de razonamiento y resolución.

### Lección 3.7: Análisis de Logs y Extracción de Información
**Descripción:** Técnicas para utilizar LLMs en la interpretación y análisis de logs de sistema y aplicaciones.

**Contenido:**
- Prompts para identificación de patrones en logs extensos
- Técnicas de resumen y categorización de eventos
- Correlación de eventos y detección de anomalías
- Extracción de métricas y KPIs a partir de logs

**Ejercicio Práctico:** 
Diseñar prompts para analizar un archivo de logs de servidor web, identificar patrones de tráfico anormal y posibles intentos de intrusión. Utilizar Gemini API con código Python para procesar y visualizar los resultados del análisis.

### Lección 3.8: Brainstorming de Arquitecturas y Soluciones
**Descripción:** Métodos para utilizar LLMs como colaboradores en el diseño de arquitecturas y soluciones técnicas.

**Contenido:**
- Técnicas para especificación de requisitos y restricciones
- Prompts para generación de múltiples enfoques arquitectónicos
- Evaluación comparativa de alternativas de diseño
- Refinamiento iterativo de soluciones propuestas

**Ejercicio Práctico:** 
Crear un prompt detallado para diseñar la arquitectura de un sistema de procesamiento de datos en tiempo real, especificando requisitos de escalabilidad, latencia y disponibilidad. Implementar en múltiples plataformas (ChatGPT, Claude y Gemini) y comparar las soluciones propuestas.
