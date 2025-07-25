# 📦 Proyecto ETL y Visualización - Bodega de Datos *Fast and Safe* - Introducción a la Ciencia de los Datos

Este repositorio contiene el desarrollo completo del proceso ETL y análisis de visualización de datos aplicado a la bodega de datos **Fast and Safe**, como parte del curso **Introducción a la Ciencia de los Datos** de la **Universidad del Valle**.

## 🧑‍🎓 Autores

- Carlos Daniel Corrales Arango - *Código: 2122878*  
- José Manuel Palma - *Código: 2125182*  
- Dylan Farkas Quiza - *Código: 2183118*

---

## 📁 Estructura del Repositorio

El repositorio está organizado de la siguiente manera:

### 🔧 Proceso ETL

Incluye los notebooks responsables de extraer, transformar y cargar los datos en la bodega, divididos en:

#### 📐 Dimensiones
- `dim_ciudad_notebook.ipynb`
- `dim_cliente_notebook.ipynb`
- `dim_estado_actual_notebook.ipynb`
- `dim_fecha_notebook.ipynb`
- `dim_mensajero_notebook.ipynb`
- `dim_sede_cliente_notebook.ipynb`
- `dim_tiempo_notebook.ipynb`
- `dim_tipo_novedad_notebook.ipynb`

#### 📊 Hechos
- `hecho_novedad_notebook.ipynb`
- `hecho_servicio_notebook.ipynb`

### 📈 Reporte de Visualización

Contiene el notebook con las respuestas visuales a las preguntas planteadas a partir de la bodega de datos, utilizando herramientas gráficas y análisis interpretativo.

---
## 📖ℹ️ Instrucciones

Antes de ejecutar los notebooks, asegurese de crear el archivo `config.yml` en la carpeta `notebooks`, el archivo debe tener la siguiente estructura: 

```
fuente:
  driver: postgresql
  db: "NOMBRE DA LA BASE DE DATOS DE ORIGEN (OLTP)"
  user: "INGRESA TU USUARIO DE POSTGRES"
  password: "INGRESA TU CONTRASEÑA"
  host: localhost
  port: 5432

bodega:
  driver: postgresql
  db: "NOMBRE DA LA BASE DE DATOS DESTINO (OLAP)"
  user: "INGRESA TU USUARIO DE POSTGRES"
  password: "INGRESA TU CONTRASEÑA"
  host: localhost
  port: 5432
```



