## Proyecto 5 – Consumo energético en edificios

Este proyecto analiza datos simulados sobre consumo energético en distintos tipos de edificios. El objetivo es explorar cómo varían los niveles de energía en función de la temperatura, humedad, tipo de construcción y nivel de ocupación.


### Objetivo
Detectar patrones de consumo energético según el tipo de edificio (residencial, comercial, industrial, educativo), y analizar cómo influyen variables como temperatura, humedad y ocupación. Se busca identificar momentos de mayor demanda energética y evaluar eficiencia operativa.

### Columnas principales del dataset

- `Timestamp`: Registro de tiempo del evento.
- `Building_ID`: Identificador único del edificio.
- `Energy_Usage (kWh)`: Consumo de energía en kilowatios.
- `Temperature (°C)`: Temperatura ambiental registrada.
- `Humidity (%)`: Porcentaje de humedad relativa.
- `Building_Type`: Tipo de construcción (residencial, industrial, comercial, educativo).
- `Occupancy_Level`: Nivel de ocupación del edificio (bajo, medio, alto).

### Limpieza y análisis
Se verificó la ausencia de valores nulos y duplicados. Se transformó la columna `Timestamp` a formato datetime para análisis temporal. Se agruparon registros por hora, día y tipo de edificio para detectar patrones de consumo. Se aplicaron visualizaciones multivariadas para explorar correlaciones entre variables.

### Visualizaciones
- Gráficos de línea por hora y tipo de construcción.
- Mapas de calor por día de la semana y hora.
- Histogramas de consumo por nivel de ocupación.
- Gráficos de dispersión entre humedad y consumo energético.

### Conclusión
El análisis reveló que los edificios residenciales y comerciales presentan mayor consumo energético, especialmente en horarios de alta ocupación. Se observó una relación inversa entre humedad y consumo, lo que sugiere ajustes ambientales en función del confort. El dataset permite modelar escenarios de eficiencia energética y evaluar el impacto de condiciones ambientales en la demanda.

### Integrante responsable
- Frank González
