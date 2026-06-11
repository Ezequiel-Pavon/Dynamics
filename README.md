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
