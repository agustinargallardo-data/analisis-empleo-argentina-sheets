# analisis-empleo-argentina-sheets
# Análisis de Empleo Registrado en Argentina (2009-2018)

## Objetivo
Este proyecto tiene como fin analizar la evolución del empleo registrado en las distintas provincias de Argentina, identificando patrones estacionales y disparidades regionales mediante el procesamiento de datos históricos.

## Tecnologías y Herramientas
* **Google Sheets** (Procesamiento y Visualización)
* **Funciones Avanzadas:** `VLOOKUP` (BUSCARV), `LEFT`, `DATE`, `AVERAGE`.
* **Tablas Dinámicas:** Para la agregación y segmentación de datos por jurisdicción.

## Pipeline de Datos (Paso a Paso)
1. **Limpieza (Data Cleaning):** Se normalizaron más de 3,500 registros. Se transformó la columna de meses (texto) a un formato de fecha cronológico utilizando lógica de extracción de strings y búsqueda de matrices.
2. **Validación:** Implementación de reglas de validación para asegurar la integridad de los nombres de las provincias.
3. **Análisis:** Creación de tablas dinámicas para calcular promedios móviles y totales anuales.
4. **Visualización:** Diseño de un dashboard interactivo con:
   - Gráfico de líneas para tendencias temporales.
   - Gráfico de barras para comparativas provinciales.

## Insights Principales
* **Concentración Regional:** Se observa que la Provincia de Buenos Aires, CABA y Santa Fe concentran el mayor volumen de la fuerza laboral registrada.
* **Estacionalidad:** El gráfico de líneas revela picos de contratación recurrentes hacia el último trimestre de cada año.

---
**Autora:** Agustina Rocio Gallardo  
🎓 *Proyecto desarrollado como parte de mi formación en Data Science e IA.*
