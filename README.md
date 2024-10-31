# Sharks
Proyecto Sharks Attacks
Shark Attack Survivor - ONG de Prevención de Ataques de Tiburones
## Descripción General
Shark Attack Survivor es una organización sin fines de lucro dedicada a la prevención de ataques de tiburones. Nuestro objetivo es proteger tanto a las personas como a los tiburones mediante el análisis de datos sobre incidentes y la implementación de campañas preventivas efectivas en zonas de alta incidencia. A través de la educación y la concienciación, buscamos reducir los riesgos y fomentar una convivencia más segura con estas especies marinas.
## Datos Utilizados
Para llevar a cabo nuestro análisis, hemos recopilado un conjunto de datos amplio y detallado con los siguientes elementos:
- **Incidentes**: Listado de ataques de tiburones reportados desde 1853 hasta 2024.
- **Especies**: Tipos de tiburones involucrados en los ataques.
- **Contexto de actividad**: Información sobre la actividad que realizaban las personas al momento del ataque (por ejemplo, surf, buceo, natación).
- **Datos demográficos**: Nombre, sexo y edad de las personas afectadas.
- **Fuentes**: Archivos y referencias para validar la información recopilada.
## Proceso de Limpieza y Transformación de Datos
Para obtener insights precisos, hemos implementado un cuidadoso proceso de limpieza y preparación de los datos. Los pasos clave incluyen:
1. **Eliminación de filas duplicadas**: Para evitar datos redundantes.
2. **Eliminación y tratamiento de valores nulos (NaN)**: Asegura la consistencia de la información. 3. **Conversión de mayúsculas/minúsculas** y eliminación de espacios para estandarizar el texto. 4. **Relleno de valores NaN** en categorías relevantes para completar datos críticos.
5. **Agrupación de datos** por categorías significativas (especies, ubicaciones geográficas, etc.).
## Herramientas y Técnicas
Utilizamos diversas técnicas avanzadas de limpieza y procesamiento de datos:
- **Expresiones Regulares (Regex)** para identificar y limpiar patrones de texto.
- **Categorías específicas** que nos permiten agrupar incidentes y analizarlos por tipos de ataques y áreas geográficas.
- **Buscadores y reemplazo de palabras** para normalizar términos comunes en el dataset.
- **Filtros de relevancia** que seleccionan la información más útil para nuestras campañas preventivas.
## Retos y Soluciones
Durante el proyecto, enfrentamos varios desafíos, incluyendo:
- **Tratamiento de valores inconsistentes**: Superado mediante el uso de expresiones regulares y filtros específicos.
- **Estandarización de datos**: La normalización de datos textuales y categóricos nos permitió generar resultados más precisos.
- **Interpretación y categorización compleja de actividades**: Desarrollamos un sistema de

categorías adaptado a nuestras necesidades, logrando una interpretación clara y coherente de los datos.
## Resultados y Conclusiones
Nuestro análisis reveló información importante para la prevención de ataques de tiburones:
1. **Zonas de alta incidencia**: Identificación de ubicaciones con mayor riesgo.
2. **Patrones de actividad**: Determinación de actividades que aumentan la probabilidad de un ataque.
3. **Impacto de las campañas educativas**: Conclusiones sobre la efectividad de nuestras campañas preventivas y recomendaciones para optimizarlas.
Estos resultados nos permitirán enfocar nuestros esfuerzos en áreas y prácticas específicas, minimizando los riesgos y aumentando la seguridad de las personas que disfrutan del mar.
