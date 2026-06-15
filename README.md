# Futbol Scout — Análisis de Datos Futbolísticos

Proyecto de ciencia de datos aplicada al fútbol, orientado a scouting inteligente
y análisis de rendimiento de jugadores.

## Objetivo

Desarrollar un sistema de evaluación de potencial de jugadores basado en métricas
espaciales y cognitivas, yendo más allá de las estadísticas tradicionales (goles, asistencias).
La idea es construir perfiles de jugadores élite en sus etapas formativas y comparar
nuevos talentos contra esos perfiles.

## Stack

- **Python 3.12** — lenguaje principal
- **StatsBomb Open Data** — fuente de datos gratuita con tracking espacial
- **pandas / numpy** — procesamiento de datos
- **mplsoccer / matplotlib** — visualizaciones de campo
- **JupyterLab** — exploración y análisis

## Estructura

futbol-scout/
├── data/
│ ├── raw/# datos originales
│ └── processed/# visualizaciones y resultados
├── notebooks/
│ └── 01_exploracion.ipynb
├── src/# código reutilizable (próximamente)
└── requirements.txt

## Notebooks

| Notebook         | Descripción                                                                                            |
| ---------------- | ------------------------------------------------------------------------------------------------------ |
| `01_exploracion` | Exploración inicial de StatsBomb Open Data, mapa de pases y heatmap de Messi vs Real Madrid (Oct 2020) |

## Estado del proyecto

🚧 Fase 1 en curso — Exploración y visualización de datos
