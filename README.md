# Proyecto-GPI

Este repositorio está diseñado como un ejercicio de **replicación y organización de investigación**, cuya estructura se basa explícitamente en el esquema propuesto en el paper publicado en *Nature*:

> **Rode et al. (2021)** – *“Estimating the global economic costs of climate change”*  
> https://www.nature.com/articles/s41586-021-03883-8

## Objetivo del repositorio

El objetivo principal de este repositorio es **replicar y adaptar la estructura de archivos y carpetas utilizada en el paper original**, con el fin de garantizar:

- Transparencia metodológica  
- Reproducibilidad de los resultados  
- Claridad en la separación entre datos, código y resultados  

La organización del repositorio sigue buenas prácticas estándar en investigación empírica y replicación computacional.

---

## Estructura del repositorio

### 📁 `ORIGINAL/`

La carpeta `ORIGINAL/` **preserva la estructura original del material de replicación** provisto por los autores del paper y disponible públicamente en Zenodo:

> https://doi.org/10.5281/zenodo.5099834

Esta carpeta mantiene **intacta la jerarquía de directorios y nombres de archivos** del repositorio original, y sirve como **referencia base** para la replicación.  
El objetivo no es modificar esta estructura, sino **entenderla y reproducirla progresivamente** en el resto del repositorio.

> ⚠️ Nota: Los datos pesados, outputs intermedios y archivos generados automáticamente no se versionan en GitHub y se excluyen mediante `.gitignore`.

---

### 📁 `DATA/`

Esta carpeta busca **replicar de forma controlada** la estructura de datos del paper original, adaptándola a un entorno de trabajo propio.  
Aquí se organizarán los datos necesarios para la replicación, respetando la lógica conceptual del paper, pero sin duplicar archivos pesados que ya se encuentran disponibles externamente.

---

### 📁 `OUTPUT/`

Contiene resultados generados por los scripts (figuras, tablas, outputs intermedios).  
Estos archivos son **reproducibles** y, por buenas prácticas, **no se versionan** directamente en el repositorio.

---

### 📄 `README.md`

Este archivo documenta:
- El origen conceptual del proyecto  
- La lógica de organización del repositorio  
- La relación entre este repositorio y el paper original  

---

## Principio rector

> **El repositorio intenta imitar, de manera fiel y transparente, la estructura original del paper**, utilizando la carpeta `ORIGINAL/` como ancla conceptual y técnica, y replicando progresivamente dicha estructura en las carpetas propias del proyecto.

Este enfoque facilita tanto la replicación como la extensión futura del análisis.

---

## Referencias

- Rode et al. (2021). *Estimating the global economic costs of climate change*. **Nature**.  
  https://www.nature.com/articles/s41586-021-03883-8

- Material de replicación original (Zenodo):  
  https://doi.org/10.5281/zenodo.5099834
