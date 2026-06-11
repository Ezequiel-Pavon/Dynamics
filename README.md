# Pampa-Dynamics

Sistema inteligente de detección de obstáculos para trenes de alta velocidad.

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

[GIF]

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
