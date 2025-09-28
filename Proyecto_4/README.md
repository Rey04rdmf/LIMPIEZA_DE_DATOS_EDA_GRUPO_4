## Proyecto 4 – Permisos de obra en CABA

Este proyecto analiza datos simulados sobre permisos de obra en la Ciudad Autónoma de Buenos Aires, utilizando variables generadas por sensores industriales para representar aspectos operativos, de seguridad y eficiencia en obras civiles.

### Dataset
- Fuente: GitHub – Grupo 4 (datos simulados)
- Formato: CSV
- Registros: 10,000
- Columnas: 15

🔗 [Descargar CSV desde GitHub](https://raw.githubusercontent.com/GFrankTI/Building-Energy-dataset-extended/refs/heads/main/tprey.csv)

### Objetivo
Simular y analizar el comportamiento de permisos de obra en función de variables como temperatura, vibración, consumo energético, cantidad de trabajadores, incidentes de seguridad y sugerencias de optimización. El enfoque busca detectar patrones operativos y riesgos asociados a distintos tipos de obra.

### Columnas principales del dataset

- `Timestamp`: Fecha y hora del evento registrado.
- `Temperature (°C)`: Temperatura ambiental en el momento del evento.
- `Humidity (%)`: Porcentaje de humedad relativa.
- `Vibration_Level (Hz)`: Nivel de vibración detectado, indicador de actividad.
- `Material_Usage (kg)`: Cantidad de material utilizado.
- `Energy_Consumption (kWh)`: Consumo energético asociado al evento.
- `Worker_Count`: Número de trabajadores presentes.
- `Task_Progress (%)`: Porcentaje de avance de la tarea.
- `Safety_Incidents`: Número de incidentes de seguridad registrados.
- `Risk_Score`: Nivel de riesgo estimado.
- `Optimization_Suggestion`: Sugerencia generada para mejorar eficiencia.
- `Performance_Score`: Evaluación del desempeño del evento.

### Limpieza y análisis
Se transformaron variables temporales, se agruparon registros por día y hora, y se clasificaron eventos por rango horario y día de la semana. Se aplicaron visualizaciones multivariadas para detectar relaciones entre riesgo, consumo energético y sugerencias de optimización.

### Visualizaciones
- Histogramas y boxplots de variables numéricas.
- Gráficos de dispersión entre temperatura, humedad y vibración.
- Mapas de calor de correlaciones.
- Gráficos por rango horario y día de la semana.
- Tablas de contingencia entre variables categóricas.

### Conclusión
El análisis permitió simular escenarios de permisos de obra con distintos niveles de riesgo y eficiencia. Las sugerencias de optimización se relacionaron con variables como consumo energético, cantidad de trabajadores y progreso de tareas. El enfoque ofrece una base para modelar procesos constructivos y evaluar desempeño operativo.

### Integrante responsable
- Reinaldo Márquez

