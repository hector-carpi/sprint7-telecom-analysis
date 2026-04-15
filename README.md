# sprint7-telecom-analysis
Este repositorio contiene el análisis realizado durante el Sprint 7 del caso ConnectaTel, una empresa de telecomunicaciones con operaciones en México y Colombia.

El dataset de ConnectaTel integra información de usuarios, planes y uso real de servicios móviles (llamadas y mensajes) en Latinoamérica, e incluye valores faltantes, sentinels, outliers y problemas de calidad de datos que simulan condiciones reales del sector de telecomunicaciones, permitiendo realizar un análisis robusto del comportamiento del cliente.

## Datasets
- plans.csv
- users_latam.csv
- usage.csv

## Proceso
1. Limpieza de datos
2. Análisis exploratorio
3. Detección de outliers
4. Segmentación

## 📂 Contenido del repositorio

- `notebooks/everpeak_analysis.ipynb`
  → Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/drive/1Hbf3eQZSt9lZucbJy83Rqp9jwiH-4ci1?usp=sharing )

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `S7 Version-Estudiante-Project-ConnectaTel.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## 🧠 Objetivo del análisis

- Detectar y corregir problemas de calidad de datos (valores faltantes, sentinels y fechas inválidas)
- Diseñar un pipeline de limpieza y transformación de datos reproducible
- Analizar el comportamiento de consumo de los clientes en servicios móviles (llamadas y mensajes), incluyendo distribuciones y outliers
- Construir segmentaciones de clientes basadas en uso y características demográficas
- Generar insights estratégicos que permitan optimizar la oferta comercial, mejorar la experiencia del cliente y apoyar la toma de decisiones en ConnectaTel
