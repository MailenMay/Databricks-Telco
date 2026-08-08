# Databricks-Telco

Prácticas de gobierno de datos y arquitectura *medallion* sobre Databricks, usando un dataset del sector de telecomunicaciones.

## 📁 Contenido

### `unity-catalog-introduction/`
Introducción a **Unity Catalog**: consulta de tablas gobernadas y acceso a ubicaciones externas (external locations).
- `01.query_tables_with_unity_catalog.ipynb`
- `02.access_external_location.ipynb`

### `unity-catalog-mini-project/`
Mini proyecto end-to-end de arquitectura medallion (bronze → silver → gold) usando Unity Catalog:
1. `01.create_external_locations.ipynb` — creación de ubicaciones externas
2. `02.create_catalog_schemas.ipynb` — creación de catálogos y esquemas
3. `03.create_bronze_tables.ipynb` — ingesta de datos crudos (capa bronze)
4. `04.create_silver_tables.ipynb` — limpieza y estandarización (capa silver)
5. `05.create_gold_tables.ipynb` — modelado analítico final (capa gold)

## 🔧 Tecnologías

- Databricks Notebooks (PySpark + SQL)
- Unity Catalog
- Arquitectura medallion (bronze/silver/gold)
