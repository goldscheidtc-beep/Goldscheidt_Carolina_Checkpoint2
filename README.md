# Modelo de datos con relaciones activas y tabla de medidas core en DAX 

## Descripción del checkpoint 
Construcción del modelo de relaciones y desarrollo de las 5 medidas core en DAX.

### Relaciones
Se conectaron las tablas según lo solicitado en la consigna: Clientes, Productos y Fechas con Ventas, y Categorías con Productos. 
Se configuro en cada una de ellas la cardinalidad en uno a varios (1:N), la direccion del filtro cruzado como unica y las realciones activadas: corroborando que todas tengan la linea entera y no punteada.

### Calendario
Creé la tabla de Dim_Fechas con CALENDAR, agregué las columnas de temporalidad y la marqué como tabla de fechas con la columna date.

### Medidas
Se creó la tabla de _Medidas, sin la columna 1, verificando en el panel de datos el icono correspondiente (calculadora).

### Medidas DAX
Se creó dentro de la tabla _Medidas, las medidas DAX: Total Ventas (para sumar las ventas), Ventas Online (solo del canal online), Ventas YTD (ventas del año actual), Ventas LY (ventas del año pasado) y % Crecimiento (para ver la diferencia)

### Validacion
Se crea una nueva pagina de validacion con una matriz para verificar que las medidas funcionan correctamente.
