# N8N-MCP-Consulta

**Descripción**

Este proyecto implementa un Modelo de Consulta Personalizado (MCP) diseñado para interactuar de forma dinámica con una base de datos alojada en Supabase, la cual contiene registros históricos y actuales de análisis de laboratorio (como dureza, cloruros, pH, turbidez, entre otros). Su propósito es permitir la consulta automatizada y contextualizada de resultados, facilitando la interpretación de datos críticos en procesos de control de calidad, diagnóstico ambiental o aseguramiento de procesos industriales.

Componentes principales del sistema:

<img src="https://github.com/Robchem95/N8N-MCP-Consulta/blob/main/FOTOS%20MCP/MCP%20Server.png" width="300"/>
<img src="https://github.com/Robchem95/N8N-MCP-Consulta/blob/main/FOTOS%20MCP/MCP%20Cliente.png" width="300"/>


Base de Datos Supabase: Contiene estructuras optimizadas con tablas relacionales que almacenan clientes, tipos de análisis, fechas de muestreo y resultados cuantitativos. Incluye funciones de autenticación, control de accesos y trazabilidad.

<img src="https://github.com/Robchem95/N8N-MCP-Consulta/blob/main/FOTOS%20MCP/Base%20de%20datos.png" width="300"/>


MCP (Modelo de Consulta Personalizado): Desarrollado con capacidades de procesamiento de lenguaje natural, permite a los usuarios realizar preguntas abiertas como:

“¿Cuál fue el último resultado de cloruros para el Cliente A?”

“¿Qué clientes tienen valores de turbidez superiores al límite permitido en los últimos tres meses?”

<img src="https://github.com/Robchem95/N8N-MCP-Consulta/blob/main/FOTOS%20MCP/Chat%20de%20interacci%C3%B3n.png" width="300"/>

Interfaz de Consulta: El MCP puede integrarse con interfaces como Telegram, WhatsApp, o dashboards interactivos (por ejemplo, en Power BI), lo que permite una consulta ágil y contextualizada desde cualquier dispositivo.

**Utilidad y Aplicaciones**

Monitoreo Continuo: Permite a técnicos y responsables de laboratorio acceder rápidamente a resultados sin necesidad de revisar manualmente hojas de cálculo o informes extensos.

Alertas Automáticas: Puede configurarse para detectar automáticamente resultados fuera de especificación y enviar notificaciones a los responsables.

Análisis Comparativos: El MCP puede realizar comparaciones históricas por cliente, tipo de análisis o periodo, apoyando decisiones técnicas o regulatorias.

Ahorro de Tiempo: Automatiza tareas repetitivas y reduce el tiempo de respuesta ante solicitudes de información.

