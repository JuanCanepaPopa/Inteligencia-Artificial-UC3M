# Sistema de Navegación Autónoma y Motor de Búsqueda Inteligente (IA - UC3M)

Proyecto práctico desarrollado para la asignatura de Inteligencia Artificial en el Grado de Ingeniería Informática por la Universidad Carlos III de Madrid (UC3M).

## Descripción del Proyecto

El objetivo principal es implementar un sistema capaz de simular la percepción y navegación de un agente autónomo en un mapa 2D interactivo con límites y obstáculos dinámicos.

## Componentes Principales

* **Search Engine (`SearchEngine.py`):** Algoritmos de búsqueda de caminos óptimos (pathfinding) para la toma de decisiones del agente.
* **Sistema de Percepción y Radar (`Radar.py`):** Sensorización en tiempo real para la detección de barreras y elementos del entorno.
* **Gestión Cartográfica (`Map.py`, `Location.py`, `Boundaries.py`):** Modelado geométrico del espacio de navegación y límites de movimiento.
* **Escenarios Dinámicos (`scenarios.json`):** Definición de mapas, obstáculos y condiciones de simulación mediante archivos JSON estructurados.

## Tecnologías Utilizadas

* **Lenguaje:** Python 3
* **Conceptos de IA:** Búsqueda en Espacios de Estados, Pathfinding, Agentes Inteligentes, Representación del Conocimiento y Entornos Simulados
