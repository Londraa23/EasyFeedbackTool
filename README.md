# Essay Feedback Tool

![Banner](https://img.shields.io/badge/English%20Feedback-Tool-blue?style=for-the-badge)

**Essay Feedback Tool** es una aplicación web que analiza textos en inglés escritos por estudiantes y devuelve correcciones, mejoras y sugerencias, adaptadas al nivel del usuario (A2, B1, B2, C1, C2).  
Usa **Ollama AI** para proporcionar un análisis detallado y formateado en JSON, que luego se muestra en el frontend de manera clara y visual.

## Características

- Análisis de textos en inglés según el nivel del estudiante (A2, B1, B2, C1, C2).  
- Correcciones gramaticales y ortográficas.  
- Sugerencias de estilo y mejoras de redacción.  
- Salida en **JSON** lista para ser renderizada en el frontend.  
- Resalta los errores directamente en el texto con etiquetas HTML para fácil visualización.  
- Soporta textos cortos y largos, adaptando el feedback al nivel del usuario.  

## Tecnologías usadas

- **Node.js**: Servidor backend para procesar las peticiones.  
- **Express.js**: Framework para gestionar rutas y APIs.  
- **Ollama AI**: Motor de IA para análisis de texto generativo.  
- **CORS**: Para permitir el acceso desde el frontend.  
- **dotenv**: Para gestionar variables de entorno, como la API key de Ollama.  
- **Fetch (node-fetch)**: Para realizar llamadas HTTP al API de Ollama.

