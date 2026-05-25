# Optimización de la Función Drop-Wave con Algoritmos Genéticos

Este repositorio contiene la implementación algorítmica y el reporte técnico de la optimización global de la función Drop-Wave mediante el uso de Algoritmos Genéticos de codificación real. 

Este proyecto fue desarrollado como entregable para la materia de **Búsqueda de Soluciones e Inferencia Bayesiana** en el Centro de Investigación en Ciencias (CInC) de la **Universidad Autónoma del Estado de Morelos (UAEM)**.

## Descripción del Problema

La función Drop-Wave es una función de prueba (*benchmark*) altamente multimodal. Su principal desafío radica en la presencia de múltiples mínimos locales distribuidos en forma de ondas concéntricas que castigan la falta de diversidad en la búsqueda.

- **Espacio de búsqueda:** $x_i \in [-5.12, 5.12]$
- **Mínimo global teórico:** $f(0,0) = -1$

## Estructura del Repositorio

- `/Notebook/`: Código fuente en Python con la implementación del Algoritmo Genético, operadores de cruza aritmética, mutación gaussiana y gráficos interactivos con Plotly.
- `/Reporte/`: Código fuente en LaTeX del documento técnico que justifica los hiperparámetros y la metodología.
- `/presentacion/`: Código en LaTeX (Beamer) de las diapositivas de soporte.
- `main.pdf`: Reporte final compilado.

## Instalación y Ejecución

Para ejecutar la simulación localmente y visualizar los resultados en 3D, es necesario instalar las dependencias requeridas:

### Clonar el repositorio
git clone <tu-enlace-de-github-aqui>

### Instalar dependencias
pip install -r requirements.txt
