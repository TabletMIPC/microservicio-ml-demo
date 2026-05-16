# Microservicio ML — Demo de despliegue

## Resumen
Descripción de una plantilla profesional para exponer modelos ML vía API REST. Solo se muestra arquitectura y decisiones de diseño; no se incluye código ejecutable.

## Arquitectura
- Entradas: JSON con features
- Procesamiento: validación y normalización
- Inferencia: modelo pre-entrenado (pesos sintéticos)
- Salida: JSON con score y explicación básica

## Tecnologías
Python, FastAPI, Docker, pytest, uvicorn

## Decisiones clave
- FastAPI por rapidez de desarrollo y documentación automática.
- Docker para consistencia entre entornos.
- Tests unitarios para contract testing de la API.

## Estructura conceptual del proyecto
- `app/`: código del microservicio (no incluido en este escaparate)
- `tests/`: pruebas unitarias
- `docker/`: Dockerfile y scripts
- `docs/`: diagramas y ejemplos de request/response

## Buenas prácticas adoptadas
- Validación de entrada
- Logging estructurado
- Configuración por variables de entorno

## Nota
Repositorio puramente descriptivo. Si necesita evaluar un despliegue real, podemos concertar una videollamada para mostrarle casos concretos.
