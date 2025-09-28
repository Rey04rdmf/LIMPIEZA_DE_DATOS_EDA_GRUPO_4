## Proyecto 3 – Rendimiento en construcción

Este proyecto analiza datos mensuales sobre precios de materiales, mano de obra e indicadores económicos en el sector de la construcción en distintas comunidades autónomas de España.

### Dataset
- Fuente: GitHub – Grupo 4
- Formato: CSV
- Registros: 1,386
- Columnas: 18

🔗 [Descargar CSV desde GitHub](https://raw.githubusercontent.com/GFrankTI/Building-Energy-dataset-extended/refs/heads/main/datos_unidos_meses.csv)

### Objetivo
Explorar cómo varían los precios de insumos clave y el costo de la mano de obra en el tiempo y entre regiones, y detectar correlaciones con indicadores como número de hipotecas, inmigración y edad media de la población.

### Columnas principales del dataset

- `precio`: Precio medio de vivienda por comunidad autónoma.
- `mano_obra`: Costo promedio de la mano de obra en construcción.
- `precio_Acero`: Precio unitario del acero.
- `precio_Aluminio`: Precio unitario del aluminio.
- `precio_Cemento`: Precio unitario del cemento.
- `precio_Ceramica`: Precio unitario de materiales cerámicos.
- `precio_Cobre`: Precio unitario del cobre.
- `precio_Energía`: Costo energético asociado a la construcción.
- `precio_Ligantes`: Precio de materiales ligantes (adhesivos, morteros).
- `precio_Madera`: Precio unitario de la madera.
- `num_hipotecas`: Número de hipotecas registradas.
- `num_inmigracion`: Número de personas inmigrantes registradas.
- `edad_media`: Edad promedio de la población.
- `IPC`: Índice de precios al consumidor.
- `year`: Fecha del registro (formato año-mes).
- `comunidad`: Nombre de la comunidad autónoma.

### Limpieza y análisis
Se verificó la ausencia de valores nulos y duplicados. Se agruparon las variables numéricas para calcular correlaciones, y se generaron visualizaciones como histogramas, gráficos de dispersión y mapas de calor para detectar patrones entre variables.

### Visualizaciones
- Histogramas de distribución de hipotecas.
- Gráficos de dispersión entre variables económicas y geográficas.
- Mapas de calor para visualizar correlaciones entre precios y materiales.

### Conclusión
El análisis reveló correlaciones significativas entre el precio de la vivienda y el costo de materiales como el acero, la energía y la madera. También se observaron patrones entre inmigración, edad media y número de hipotecas, lo que sugiere posibles vínculos entre dinámica poblacional y actividad constructiva.

### Integrante responsable
- Reinaldo Márquez
