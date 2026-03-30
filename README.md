# Replicación: Bayesian Workflow for Disease Transmission Modeling

Este repositorio contiene el código y los análisis realizados para la replicación de los resultados del artículo **"Bayesian workflow for disease transmission modeling in Stan"**. El objetivo principal de este proyecto es reproducir los resultados y las visualizaciones presentadas por los autores originales para el estudio de un brote de influenza en un internado británico.

## Contenido del Repositorio

* **`Proyecto.Rmd`**: Archivo principal en R Markdown con el desarrollo matemático del modelo SIR y el código de ejecución en R.
* **Modelos en Stan**: Implementaciones del modelo epidemiológico SIR utilizando ecuaciones diferenciales ordinarias (ODE) y verosimilitud.
* **Análisis y Gráficas**: Código para la generación de diagnósticos de convergencia ($\hat{R}$, $n_{eff}$), chequeos predictivos *a priori* y *a posteriori*, y estimación de parámetros latentes.

## Nota sobre la Autoría del Código

El código contenido en este repositorio **no es de autoría original total**. Es una **réplica traducida y adaptada** del trabajo de:

> **Léo Grinsztajn, Elizaveta Semenova, Charles C. Margossian y Julien Riou**
> Repositorio original: [disease_transmission_workflow](https://github.com/charlesm93/disease_transmission_workflow)

### Modificaciones realizadas:
1.  **Traducción:** La documentación y comentarios fueron traducidos al español.
2.  **Selección de Contenido:** Se omitieron secciones del flujo de trabajo original que no fueron requeridas para los objetivos específicos de nuestro informe.
3.  **Análisis Complementario:** Se añadieron interpretaciones y verificaciones basadas en el contexto del trabajo.

## Requisitos

Para ejecutar este proyecto, es necesario contar con:
* **R** y **RStudio**.
* Librerías: `rstan`, `outbreaks`, `tidyverse`, `gridExtra`.
* Un compilador de C++ configurado para trabajar con `Stan`.
