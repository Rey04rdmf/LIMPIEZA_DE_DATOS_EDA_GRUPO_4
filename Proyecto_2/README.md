## Proyecto 2 – Viviendas en España

Este proyecto analiza datos de propiedades en venta en distintas regiones de España, con el objetivo de entender cómo varían los precios según ubicación, materiales, y otras características estructurales.

### Dataset
- Fuente: Kaggle / Idealista (compilado por Indiana Torres)
- Formato: CSV
- Registros: ~55,000
- Columnas: 94

### Objetivo
Explorar las relaciones entre precio de vivienda, ubicación geográfica, tipo de propiedad, materiales de construcción y otras variables relevantes. Detectar patrones que puedan ser útiles para predicción, segmentación o análisis territorial.

### Columnas principales del dataset

- `price`: Precio de la propiedad en euros.
- `province`: Provincia donde se ubica la propiedad.
- `municipality`: Municipio específico.
- `property_type`: Tipo de propiedad (piso, casa, chalet, etc.).
- `surface`: Superficie construida en m².
- `rooms`: Número de habitaciones.
- `bathrooms`: Número de baños.
- `floor`: Piso en el que se encuentra.
- `material`: Material predominante de construcción.
- `condition`: Estado de la propiedad (reformado, nuevo, a reformar).
- `energy_certificate`: Certificación energética.
- `latitude` y `longitude`: Coordenadas geográficas.
- `date_posted`: Fecha de publicación del anuncio.
- `has_lift`, `has_garage`, `has_pool`: Indicadores de amenidades.

### Limpieza y análisis
Se realizó una depuración de columnas vacías o redundantes, normalización de precios y superficies, conversión de variables categóricas, y geolocalización de propiedades. Se aplicaron filtros por provincia y se agruparon propiedades por tipo y estado.

### Visualizaciones
- Mapas de calor por provincia y municipio.
- Histogramas de precios y superficies.
- Gráficos de dispersión entre precio y características estructurales.
- Series temporales de publicaciones.

### Conclusión
El análisis reveló fuertes correlaciones entre ubicación, tipo de propiedad y precio. Las propiedades reformadas y con materiales de calidad presentan precios significativamente más altos. El dataset ofrece un alto potencial para aplicar modelos de regresión, clustering y análisis geoespacial.

### Integrante responsable
- Indiana Torres
