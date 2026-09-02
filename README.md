# Dynamics

Sistema inteligente de detección de obstáculos para vehiculos de alta velocidad.

## Tecnologías

- Python
- OpenCV
- YOLOv8
- NumPy
- Streamlit

## Características

- Detección de personas
- Detección de vehículos
- Detección de animales
- Sistema de alertas
- Dashboard en tiempo real

## Demo

<img width="1536" height="1024" alt="ChatGPT Image 10 jun 2026, 10_28_58 p m" src="https://github.com/user-attachments/assets/5c1490f0-b9da-42e6-a495-822e9fed234c" />

## Arquitectura

                   VIDEO
                     │
                     ▼
                   OpenCV
                     │
                     ▼
                  YOLOv8
                     │
        ┌────────────┼────────────┐
        ▼            ▼            ▼
    Persona      Vehículo      Animal
        │            │            │
        └────────────┼────────────┘
                     ▼
             Sistema de Alertas
                     │
          ┌──────────┴──────────┐
          ▼                     ▼
     Base de datos         Dashboard
                     │
                     ▼
              Video procesado

<hr/>


Copyright (c) [2026] [Howieze]

Todos los derechos reservados.

Este repositorio y todo su contenido (incluyendo pero no limitado a textos,
artículos, imágenes, código fuente, diseño y estructura del sitio) es
propiedad exclusiva del autor mencionado arriba.

Se permite:
  - Ver y leer el contenido publicado en este sitio.
  - Compartir enlaces directos a las publicaciones, citando la fuente
    original con un enlace de vuelta a este repositorio o sitio web.

No se permite, sin autorización previa y por escrito del autor:
  - Copiar, reproducir, distribuir o republicar total o parcialmente
    el contenido de este repositorio en cualquier otro sitio, blog,
    plataforma o medio.
  - Modificar, traducir o crear obras derivadas del contenido.
  - Usar el contenido con fines comerciales.
  - Reutilizar el código fuente del sitio para crear un sitio derivado.

Cualquier uso no autorizado de este contenido constituye una violación
de los derechos de autor y podrá dar lugar a las acciones legales
correspondientes, incluyendo solicitudes de retiro de contenido (DMCA)
en las plataformas donde se aloje el contenido copiado.

Para solicitar autorización de uso, contactar a: [eduardoezequielpavon20044@gmail.com]



