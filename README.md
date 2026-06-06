# Proyecto final de Demografía 9219: Estado de Chiapas

## Descripción

Este repositorio contiene el proyecto final de la materia **Demografía 9219**, enfocado en el análisis demográfico del estado de **Chiapas**.

El trabajo fue desarrollado en **R** y **Quarto**, y genera un documento final en PDF. Se analizan tablas de vida, esperanza de vida, causa eliminada por homicidios y medidas sintéticas de fecundidad.

## Autora

Campos Ruiz Evelyn Paola

## Entidad analizada

Chiapas, México.

## País de comparación

Chile.

## Objetivo del proyecto

Analizar la dinámica demográfica de Chiapas a partir de indicadores de mortalidad y fecundidad, considerando:

- Pirámides poblacionales.
- Tablas de vida para 2010, 2019 y 2021.
- Esperanza de vida al nacer por sexo.
- Tasas de mortalidad por edad.
- Defunciones de la tabla de vida.
- Tabla de causa eliminada por homicidios.
- Tasa Global de Fecundidad.
- Tasa Bruta de Reproducción.
- Tasa Neta de Reproducción.
- Comparación de Tasas Específicas de Fecundidad en 2019 entre Chiapas, México y Chile.

## Fuentes de información

Las fuentes principales utilizadas fueron:

- INEGI: defunciones registradas, homicidios por edad, sexo y año.
- INEGI: Censos de Población y Vivienda 2010 y 2020.
- CONAPO: indicadores demográficos y proyecciones poblacionales.
- World Population Prospects 2024: datos de fecundidad para México y Chile.
- Cálculos propios realizados en R.

## Metodología

Se construyeron tablas de vida abreviadas por sexo y año. Para ello se calcularon:

- Tasa central de mortalidad.
- Probabilidad de muerte.
- Probabilidad de supervivencia.
- Sobrevivientes.
- Defunciones de la tabla.
- Años-persona vividos.
- Esperanza de vida.

También se aplicó una tabla de causa eliminada para estimar el efecto de los homicidios sobre la esperanza de vida en Chiapas durante 2019.

Para fecundidad se calcularon:

- Tasa Específica de Fecundidad.
- Tasa Global de Fecundidad.
- Tasa Bruta de Reproducción.
- Tasa Neta de Reproducción.
- Nivel de reemplazo.

## Estructura del repositorio

```text
ProyectoFinal.Demografia.9219/
│
├── README.md
├── ProyectoFinal_Chiapas_9219.qmd
├── ProyectoFinal-Chiapas-9219.pdf
│
├── data/
│   ├── raw/
│   └── clean/
│
├── output/
│   ├── tablas/
│   └── figuras/
│
└── referencias/