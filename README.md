# Matias Rebolledo

Data and platform engineer based in Barcelona. I build the pipelines, infrastructure and validation tooling that scientists, statisticians and analysts rely on, with geospatial and scientific data as my specialty.

## What I work on

- **Data platforms** - batch pipelines and data lake architecture (Spark, Airflow, Trino, MinIO, Apache Iceberg), metadata and lineage (OpenMetadata), DuckDB for lightweight registries.
- **Geospatial and scientific data** - GDAL, Rasterio, GeoPandas, xarray, PostGIS; GeoTIFF/COG, NetCDF, Parquet, STAC.
- **HPC and deployment** - Slurm, Ansible, Docker/Singularity, GitLab CI/CD, Linux automation.
- **Validation services** - FastAPI services and QC gates that stop bad data before it reaches downstream users.

## Background

13+ years across quantitative analysis, official statistics and scientific computing. I started in statistics and econometrics, moved into geospatial data production and national-scale data lake engineering, and now work on climate model data pipelines (CMIP) at the Barcelona Supercomputing Center.

## Currently exploring

- Spatio-temporal inference on noisy data: GPS probe traces, map-matching, speed and closure estimation.
- Decision rules under uncertainty: ranking competing actions or alerts by probability x consequence.
- Combinatorial designs and their computational side (enumeration, search, GPU/HPC performance).
- A typed systems language for production services alongside Python.

## Selected work

- [`probe-traffic-lab`](https://github.com/mat21mf/probe-traffic-lab) - noisy GPS probes to per-segment speeds and closures: HMM map-matching and estimation prototyped in Python, production core in a typed language, evaluated against known ground truth.
- [`sandbox-rag-mcp`](https://github.com/mat21mf/sandbox-rag-mcp) - RAG scaffold for restricted environments: offline embedding, prebuilt LanceDB index, HF-free ONNX query path, and an MCP server that orchestrates a GPU workstation.
- [`gdal-parquet`](https://github.com/mat21mf/gdal-parquet) - reproducible source build of GDAL 3.9 with GeoParquet, PROJ, GEOS and TileDB.
- [`quiz_spaceag`](https://github.com/mat21mf/quiz_spaceag) - Sentinel-2 NDVI time series for 33 avocado plots (2016-2020): shell ETL into per-plot daily grids, GeoPandas analysis and visualization.

Most of my professional work lives in institutional repositories.

**Contact:** [LinkedIn](https://www.linkedin.com/in/matias-felipe-rebolledo-871494251) | el4ur22lh@mozmail.com
