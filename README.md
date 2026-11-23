# Jardinería: proceso ETL y Data Mart

Proceso ETL (extracción, transformación y carga) de la base de datos
Jardinería hacia un Data Mart con modelo estrella, en MySQL.
Evidencia de aprendizaje 3, Bases de Datos II, IU Digital de Antioquia.

**Autora:** Yenni Vanessa Delgado Velasco

## Recorrido de los datos

`jardineria` (origen) → `jardineria_staging` (Staging y transformación) → `dm_jardineria` (Data Mart)

## Contenido
| Archivo | Qué hace |
|---|---|
| `EA3_informe_yenniDelgado.pdf` | Informe del proyecto en PDF (APA 7) |
| `02_carga_staging.sql` | Crea Staging y carga las tablas |
| `03_verificacion_staging.sql` | Verifica integridad y consistencia |
| `04_perfilado_staging.sql` | Perfila los datos |
| `05_limpieza_y_estandarizacion.sql` | Catálogo de región y correcciones |
| `06_derivacion_calendario.sql` | Tabla calendario e importe de venta |
| `07_vistas_transformacion.sql` | Vistas de clientes, productos y ventas |
| `08_carga_dimensiones.sql` | Carga las dimensiones |
| `09_carga_tabla_hechos.sql` | Carga la tabla de hechos |
| `10_verificacion_carga.sql` | Verifica la carga |
| `11_analisis.sql` | Consultas analíticas |
| `12_prueba_restauracion.sql` | Compara lo original con lo restaurado |
| `BK_*.sql` | Copias de seguridad de las tres bases de datos |
