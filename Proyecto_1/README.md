## Proyecto 1 – Presupuestos NYC

Este proyecto analiza datos de presupuestos y programas gubernamentales en la ciudad de Nueva York.

### Dataset
- Fuente: NYC Open Data
- Formato: CSV
- Registros: ~12000
- Columnas: 15

### Objetivo
Explorar cómo se distribuyen los fondos públicos entre distintas áreas y programas, y detectar patrones de asignación presupuestaria.

### Columnas principales del dataset

- `Agency`: Nombre del organismo gubernamental responsable.
- `Department`: Departamento específico dentro del organismo.
- `Program`: Nombre del programa financiado.
- `Budget Category`: Tipo de gasto (capital, operativo, etc.).
- `Fiscal Year`: Año fiscal al que corresponde el presupuesto.
- `Amount Allocated`: Monto asignado en dólares.
- `Amount Spent`: Monto efectivamente gastado.
- `Program Type`: Clasificación del programa (educación, salud, vivienda, etc.).
- `Location`: Ubicación geográfica del programa (distrito o zona).
- `Status`: Estado del programa (activo, finalizado, suspendido).
- `Funding Source`: Fuente de financiamiento (local, federal, mixto).
- `Start Date` y `End Date`: Fechas de inicio y fin del programa.
- `Priority Level`: Nivel de prioridad asignado por el gobierno.
- `Impact Score`: Indicador estimado del impacto social del programa.

### Limpieza y análisis
Se realizó una limpieza de columnas irrelevantes, normalización de nombres y conversión de tipos de datos para facilitar el análisis. Se agruparon los programas por categoría y se analizaron tendencias temporales.

### Visualizaciones
- Gráficos de barras por categoría de programa.
- Series temporales para observar evolución presupuestaria.
- Agrupaciones por área temática para detectar prioridades de inversión.

### Conclusión
El análisis reveló una fuerte concentración de fondos en áreas como educación, salud y vivienda. Se identificaron patrones de asignación que podrían ser útiles para evaluar la equidad presupuestaria y proponer mejoras en la distribución de recursos.

### Integrante responsable
- Petty Peña

