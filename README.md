# Cierre Contable – Analytics & Reporting

Repositorio técnico para el proyecto de analítica y soporte al proceso de
cierre contable (transformaciones, validaciones, métricas y reporting).

---

## Arquitectura lógica
Fuentes iniciales excel de cierre contabilidad Ingresos y Gastos → Sharepoint → Power BI

---

## Estructura del repositorio
cierre-contable/
- docs_negocio/ # Carta, acuerdos, definiciones de negocio
- dbt/ # Transformaciones (SQL) y reglas de negocio
- notebooks/ # EDA, reconciliaciones, pruebas
- src/ # Código Python productivo (validaciones/automatización)
- docs/ # Documentación técnica (diccionario, calidad, arquitectura)
-  requirements.txt
- .gitignore
- README.md

## Stack técnico
- Python 3.11
- dbt
- DuckDB (dev local)
- Git / GitHub