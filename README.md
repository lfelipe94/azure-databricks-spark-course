# Azure Databricks y Spark Course - Proyecto Final

## 📚 Descripción del Proyecto

Este repositorio contiene el proyecto final del curso de **Azure Databricks y Spark** de Udacity. El proyecto demuestra el uso de Apache Spark para el procesamiento de datos a gran escala utilizando Azure Databricks como plataforma de análisis.

## 🎯 Objetivos del Proyecto

- Implementar un pipeline de datos completo usando Apache Spark
- Procesar y analizar datasets de transporte público
- Crear tablas optimizadas en Azure Databricks
- Implementar consultas SQL eficientes para análisis de datos
- Generar insights valiosos a partir de datos de viajes y estaciones

## 🏗️ Arquitectura del Proyecto

El proyecto incluye:

- **Datasources**: Datasets de entrada (payments.csv, riders.csv, stations.csv, trips.csv)
- **Notebooks Jupyter**: Análisis y procesamiento de datos
- **Diagramas ERD**: Modelo de datos y relaciones entre entidades
- **Documentación**: Archivos PDF y diagramas explicativos

## 📊 Datasets Utilizados

- **trips.csv**: Información sobre viajes realizados
- **riders.csv**: Datos de los usuarios del servicio
- **stations.csv**: Información de las estaciones disponibles
- **payments.csv**: Datos de transacciones y pagos

## 🚀 Tecnologías Utilizadas

- **Apache Spark**: Motor de procesamiento de datos distribuido
- **Azure Databricks**: Plataforma de análisis unificada
- **Python**: Lenguaje de programación principal
- **Jupyter Notebooks**: Entorno de desarrollo interactivo
- **SQL**: Consultas para análisis de datos

## 📁 Estructura del Repositorio

```
├── datasources/                    # Datasets de entrada
│   ├── payments.csv
│   ├── riders.csv
│   ├── stations.csv
│   └── trips.csv
├── Udacity Project Luis Serna.ipynb # Notebook principal del proyecto
├── ERD Udacity Project Luis Serna.drawio.pdf # Diagrama de entidad-relación
├── EDR Project.png                 # Imagen del diagrama ERD
├── Tables in hive_metastore_default_db.png # Captura de tablas en Databricks
└── README.md                       # Este archivo
```

## 🔧 Instalación y Configuración

1. Clona este repositorio:
   ```bash
   git clone https://github.com/lfelipe94/azure-databricks-spark-course.git
   cd azure-databricks-spark-course
   ```

2. Abre el notebook principal en Jupyter:
   ```bash
   jupyter notebook "Udacity Project Luis Serna.ipynb"
   ```

3. Asegúrate de tener las dependencias necesarias instaladas:
   ```bash
   pip install pyspark pandas numpy matplotlib seaborn
   ```

## 📈 Resultados del Proyecto

El proyecto demuestra:
- Procesamiento eficiente de grandes volúmenes de datos
- Creación de tablas optimizadas en Databricks
- Análisis de patrones de uso del transporte público
- Implementación de consultas SQL complejas
- Visualización de datos y generación de insights

## 👨‍💻 Autor

**Luis Serna Velásquez**
- Estudiante del curso Azure Databricks y Spark de Udacity
- Especialización en procesamiento de datos y análisis

## 📚 Recursos Adicionales

- [Documentación oficial de Apache Spark](https://spark.apache.org/docs/latest/)
- [Azure Databricks Documentation](https://docs.azuredatabricks.net/)
- [Curso Udacity - Azure Databricks and Spark](https://www.udacity.com/)

## 📄 Licencia

Este proyecto es parte del curso de Udacity y está destinado únicamente para fines educativos.

---

⭐ Si este proyecto te resulta útil, ¡no olvides darle una estrella! 